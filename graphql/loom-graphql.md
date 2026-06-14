# Loom GraphQL Schema

This document describes the conceptual GraphQL schema for the Loom async video messaging platform. Loom exposes its capabilities through REST APIs (recordSDK, embedSDK, oEmbed, SCIM) and this schema represents a unified GraphQL surface over those capabilities.

## Provider

- **Name:** Loom
- **Website:** https://www.loom.com/
- **Developer Portal:** https://dev.loom.com/
- **API Docs:** https://support.loom.com/hc/en-us/articles/4420225668251
- **Parent Company:** Atlassian

## Schema File

- [loom-schema.graphql](loom-schema.graphql)

## Type Summary

The schema covers the following capability areas:

### Video Core
`Video`, `VideoDetails`, `VideoTitle`, `VideoDescription`, `VideoTranscript`, `TranscriptWord`, `TranscriptCaption`, `VideoThumbnail`, `VideoTimestamp`, `VideoLink`

### Engagement
`VideoReaction`, `VideoComment`, `CommentTimestamp`, `Chapter`, `ChapterTitle`, `ChapterSummary`, `VideoSummary`, `AISummary`, `SummaryHighlight`

### Sharing and Privacy
`ShareLink`, `EmbedCode`, `VideoPrivacy`, `VideoPassword`, `AllowedEmails`, `AllowedDomains`

### Recording
`Recording`, `RecordingSettings`, `CameraLayout`, `ScreenLayout`, `SpeakerLayout`, `AudioSettings`, `VideoQuality`, `Resolution`

### Workspace and Organization
`Workspace`, `WorkspaceDetails`, `WorkspaceFolder`, `Folder`, `FolderDetails`, `FolderAccess`

### Members and Permissions
`Member`, `MemberRole`, `MemberPermission`

### Integrations
`Integration`, `SlackIntegration`, `JiraIntegration`, `NotionIntegration`

### Playlists
`Playlist`, `PlaylistVideo`

### Analytics
`Analytics`, `VideoAnalytics`, `ViewCount`, `ViewDuration`, `EngagementRate`, `Viewer`, `ViewerDetails`

### Auth and Webhooks
`APIKey`, `Token`, `Webhook`

## Notes

Loom does not publish a public GraphQL endpoint. This schema is a conceptual representation based on the documented REST API surface and the capabilities described in the Loom developer documentation. It is intended to support API discoverability, tooling, and developer experience research.
