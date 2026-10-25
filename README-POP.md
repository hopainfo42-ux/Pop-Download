# Pop Download

Modern Download Manager for Windows — customized by **Ehap Ahmed**.

**Status:** Development starter kit. No verified executable is included.

Based on [Ezoo Download v1.0.5](https://github.com/AhmedEzo686/ezoo-download/tree/v1.0.5) by Ahmed Ezzat. Preserve original attribution and third-party notices.

## Windows setup
1. Install Git for Windows and Python 3.
2. Unzip this package anywhere.
3. Run `SETUP_POP_DOWNLOAD.bat`. It clones the original source **v1.0.5**, copies it to a PopDownload folder, and applies branding to that folder.
4. Open GitHub Desktop > File > Add local repository > Choose the `PopDownload` folder. If prompted, create a repository there.
5. Before publishing, inspect changes and test with `cargo build --release`.
6. In GitHub Desktop choose Repository > Repository settings > Remote > URL: `https://github.com/hopainfo42-ux/Pop-Download.git`.
7. Commit and push ONLY when ready. Do not push to the unrelated `pure-water-store` repository.

### What the patch does
- Renames Windows app/installer to Pop Download, credits Ehap Ahmed as derivative maintainer.
- Replaces PNG/ICO branding assets with the user-provided logo.
- Uses blue/cyan accent, starts from Windows light/dark setting.
- Creates a separate application data folder.
- Disables automatic upstream software updates until Pop Download has its own signed release channel.

### Still to do
- Runtime theme-change detection (initial Windows preference only)
- Full redesign of dialogs, onboarding, Arabic layout, updated About screen
- Signing and opt-in updates from Pop Download Releases
- Thorough Windows testing before publishing any installer
- Audit authentication, security, and applicable project licenses
