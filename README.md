# Worldprofit Social Codex Plugin

Create branded, image-enhanced posts for the Worldprofit Facebook page, X account, and LinkedIn personal profile and company Page, plus Instagram feed posts for @worldprofit, with an explicit approval step before publishing or scheduling.

## Install in Codex

```powershell
codex plugin marketplace add georgekosch-glitch/worldprofit-social-plugin --ref main
codex plugin add worldprofit-social@worldprofit
```

Restart Codex and begin a new task after installation.

Publishing uses the authenticated Facebook, X, LinkedIn, and Instagram browser sessions on the computer where Codex is running. Browser logins are not stored in this repository or transferred between computers.

The plugin includes the confirmed LinkedIn profile and company Page URLs. Sign in on the posting computer. Company Page posting requires permission to publish as that Page. Each destination is included separately in the approval package.

Instagram uses https://www.instagram.com/worldprofit/ by default, for feed image posts only. Sign into @worldprofit on the posting computer. Stories and Reels are outside the configured scope. Review the caption and final image before approving publication.
