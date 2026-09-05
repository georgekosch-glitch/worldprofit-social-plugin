---
name: worldprofit-social-posts
description: Create image-enhanced Worldprofit social posts for its Facebook page and official group, X account, LinkedIn personal profile, and LinkedIn company Page, and Instagram feed, obtain explicit approval, and then publish or schedule the approved versions. Use for Worldprofit social campaigns, post drafts, content calendars, and approved posting.
---

# Worldprofit Social Posts

Create polished, platform-native social posts while preserving an approval boundary before any external posting or scheduling.

## Brand context

On first use, ask for or inspect the Worldprofit website, logo, brand colors, preferred calls to action, audience, and any compliance rules relevant to the campaign. Reuse confirmed brand facts in later work, but verify details that may have changed. Do not invent product claims, prices, testimonials, results, guarantees, or deadlines.

If brand assets are supplied, use them as references. When no usable visual asset exists, generate an original image aligned with the confirmed brand direction. Do not imitate third-party copyrighted campaigns or place text-heavy copy inside the image.

## Drafting

Produce distinct versions rather than copying one caption verbatim:

- Facebook Page: conversational, enough context to stand alone, a clear call to action, and restrained hashtag use.
- Facebook group: use a community-focused caption with useful context and an invitation to discuss, adapted to the group's rules.
- LinkedIn personal profile: use a personal professional perspective, a useful takeaway, and a natural invitation to discuss.
- LinkedIn company Page: use Worldprofit's brand voice, business value, and a clear call to action. Prepare a distinct caption from the personal-profile version.
- Instagram feed: create an image-led caption with a clear opening, useful context, and restrained relevant hashtags. Include the final image crop and alt text for approval. Verify any proposed link-in-bio destination before using that call to action.
- X: concise and immediately understandable, within the platform's current post limit, with only useful hashtags or mentions.

For each campaign, prepare an approval package containing:

- the exact Facebook Page and group text, labeled separately for the requested destinations;
- the exact X text;
- the exact Instagram feed caption when requested;
- the exact LinkedIn personal-profile and company-Page text, labeled separately when requested;
- the final image or images and meaningful alt text;
- destination links and any tracking parameters;
- the intended accounts;
- either "publish now" or the proposed date, time, and timezone.

Flag assumptions and claims needing verification. If the user asks for variations, keep each option complete enough to approve independently.

## Approval boundary

Drafting and image generation do not authorize publication. Before any external post, upload, queue, or scheduling action, obtain explicit approval for the exact approval package. Treat edits after approval as invalidating that approval unless they are purely mechanical platform formatting that does not change meaning; disclose any such formatting.

Approval for the Facebook Page does not authorize posting to the group, or vice versa. Both may be approved together when clearly labeled.

Approval for one platform or posting identity does not authorize another. LinkedIn personal-profile and company-Page posts require separately identified approval, which may be given together in one package. Approval for one time does not authorize a different time. Never approve content on the user's behalf.

## Publish now

After explicit approval, use an available connected social tool when one is installed. Otherwise use browser control with the user's already authenticated Facebook, X, LinkedIn, and Instagram sessions. Verify the destination account and preview immediately before submission. Stop for the user if login, multi-factor authentication, account selection, permissions, or a platform warning requires judgment.

After submission, confirm the visible result and report the platform, timestamp, and post URL when available. Do not repeatedly submit after an ambiguous result; inspect first to avoid duplicates.

## Facebook group destination

Saved Worldprofit official group: https://www.facebook.com/groups/worldprofit

Use this URL when the user requests the Worldprofit group; do not ask for it again. Treat the group and Facebook Page as separate destinations. Include the group for an explicit all-destinations campaign; do not silently expand an ambiguous Facebook-only request to both destinations. Reuse a confirmed choice or clarify it in the approval package.

Use the authenticated Facebook browser session or an available connected tool that explicitly supports group posting. Before uploading or submitting, verify the group URL, the posting identity (personal profile or Page), posting access, and visible group rules. Do not assume Page posting rights grant group access or that an API supports groups. Ask for the posting identity only if it is not already confirmed and the choice matters.

Verify the result after submission. If the post is pending moderator approval, report it as pending rather than published, and do not resubmit it. Record a post URL when available. Scheduling is available only when confirmed in the current interface or through the approved scheduled-task fallback. Saving this destination does not authorize any post or membership/settings changes.

## LinkedIn destinations

Saved destinations confirmed by George Kosch:

- Personal profile: https://www.linkedin.com/in/georgekosch
- Worldprofit company Page: https://www.linkedin.com/company/240475/
- Company Page admin dashboard: https://www.linkedin.com/company/240475/admin/dashboard/

Use both LinkedIn destinations by default when LinkedIn is requested, unless the user specifies one destination or overrides these URLs. Do not ask the user to provide these URLs again. The admin URL is for managing the Page; use the public Page URL in audience-facing copy. Saved destinations do not authorize publication or establish that the current browser session has Page permissions.

Support both the user's personal profile and the Worldprofit company Page. Reuse confirmed destination choices; ask for the exact profile or Page URL when identity is ambiguous. Confirm the user can publish on the selected Page and verify the composer identity before any upload or submission. Never substitute the personal profile when Page publishing is unavailable. Ask the user to complete sign-in or obtain Page access when required; do not request passwords in chat or store credentials in the repository.

Create and verify each LinkedIn destination independently. If one succeeds and the other fails, retain the successful post's receipt and retry only the failed destination after checking for duplicates. Do not claim a LinkedIn API connection exists: browser posting uses the signed-in session unless an available connected tool actually supports the requested action.

## Instagram destination and scope

Saved Instagram account: @worldprofit — https://www.instagram.com/worldprofit/

Use this destination whenever Instagram is requested; do not ask for the URL again unless the user changes accounts. Scope is feed image posts only. Do not create Stories, Reels, or video posts unless the user explicitly expands scope. Default to a single image; use a carousel only when requested and approve all images and their order.

Use the authenticated Instagram browser session or an available connected tool that supports feed publishing. Verify the active account is @worldprofit and inspect the feed-post preview, image crop, caption, and available alt-text controls before publishing. Check current media requirements in the publishing interface rather than assuming fixed limits. Saved account details do not establish authentication or API access. If sign-in or account access is missing, ask the user to complete it; never request credentials in chat. After posting, verify the feed post and record its URL. Apply the same explicit approval and duplicate-prevention rules as other platforms.

## Schedule

When the platform offers native scheduling, schedule the approved post there and verify the queued item. If native scheduling is unavailable, create a Codex scheduled task that wakes at the approved time to perform the posting workflow. Make clear that a wake-up task may still require the authenticated browser session and that platform-side scheduling is more reliable when available.

Always include an explicit timezone and confirm the final scheduled date and time. For recurring campaigns, ask whether every occurrence uses pre-approved fixed content or requires a fresh approval package. Default to fresh approval for changing content.

## Completion record

Return a compact receipt listing each platform as drafted, approved, scheduled, published, failed, or awaiting user action. Include scheduled times and live links where available. Preserve draft status when no external action occurred.
