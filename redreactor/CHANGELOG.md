# Changelog since 0.1.6
- Rename add-on to app (#55) 
- 📌 Pin shared workflows to hassio-addons/workflows v4.0.0

Replace the @main and untagged commit references with the v4.0.0
release commit so every run uses a known, versioned workflow.

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
Claude-Session: https://claude.ai/code/session_01VpoEuBAuro3EAkZgHqh67c 
- 🔥 Remove 32-bit architecture support

The shared hassio-addons CI no longer builds armhf, armv7 or i386, so
drop them from app configs, build files, Renovate matchers and the
architecture badges. aarch64 and amd64 remain supported.

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
Claude-Session: https://claude.ai/code/session_01VpoEuBAuro3EAkZgHqh67c 
- 🎨 Move workflow pin comment onto its own line

Prettier collapses the space before a trailing comment to one, while
yamllint requires two; a standalone comment satisfies both.

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
Claude-Session: https://claude.ai/code/session_01VpoEuBAuro3EAkZgHqh67c 
- 🔒 Pin shared app workflows to a commit

Pin hassio-addons app-ci/app-deploy reusable workflows to a commit
hash, as required by zizmor's unpinned-uses policy.

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
Claude-Session: https://claude.ai/code/session_01VpoEuBAuro3EAkZgHqh67c 
- 🚚 Rename add-ons to apps

Home Assistant renamed add-ons to apps in 2026.2. Update user-facing
wording, repository references and shared workflow names to match.

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
Claude-Session: https://claude.ai/code/session_01VpoEuBAuro3EAkZgHqh67c 
- ⬆️ Update home-assistant/cli to v5.5.0 (#51)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com> 
- ⬆️ Update home-assistant/cli to v5.4.0 (#50)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com> 
- ⬆️ Update home-assistant/cli to v5.3.1 (#49)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com> 
- ⬆️ Update home-assistant/cli to v5.3.0 (#48)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com> 
- ⬆️ Update home-assistant/cli to v5.2.0 (#47)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com> 
- ⬆️ Update redreactor to v0.1.8 (#46) 
- ⬆️ Update redreactor to v0.1.8 
