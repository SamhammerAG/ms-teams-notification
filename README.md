<p>
  <a href="https://github.com/SamhammerAG/ms-teams-notification/actions"><img alt="ms-teams-notification status" src="https://github.com/SamhammerAG/ms-teams-notification/workflows/Build%20&%20Test/badge.svg"></a>
</p>

Continues https://github.com/marketplace/actions/microsoft-teams-notification

⚠️ Should not be used anymore, we now need to use another action to support new format used by microsofot workflows.

More Information https://github.com/jdcargile/ms-teams-notification/issues/70#issuecomment-2465431981

Usage:
```yaml
- name: Microsoft Teams Notifications
  uses: Samhammer/ms-teams-notification@v1
  with:
    github-token: ${{ github.token }} # this will use the runner's token.
    ms-teams-webhook-uri: ${{ secrets.MS_TEAMS_WEBHOOK_URI }}
    notification-summary: Your custom notification message 
    notification-color: 17a2b8
    timezone: Europe/Bucharest
```

For more details on syntax and parameteres see https://github.com/jdcargile/ms-teams-notification
