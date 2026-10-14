# Privacy and responsible use

Beyond the Title — Professional Connection Cards is designed to minimize data collection and keep the participant in control.

## Data handling

- Form values are processed in the browser.
- There is no application backend, analytics service, database, account, or telemetry.
- Values are stored in browser local storage under `beyond-the-title.v2` so the form can be restored on that device.
- **Clear saved data** removes the stored profile from the current browser.
- **Export JSON** downloads a local copy chosen by the participant.
- **Import JSON** reads only the file selected by the participant.

## External network request

The application loads `html2canvas` from cdnjs for PNG generation. The CDN may receive ordinary request metadata such as IP address, browser information, and timestamp. The application does not attach form values to that request. If this dependency is unavailable, the card still works and can be captured in screenshot mode, but direct PNG download will be unavailable.

## Sensitive fields

Phone numbers, LinkedIn URLs, professional challenges, and personality results can be sensitive in context. Every field is optional. Before downloading or sharing a card:

1. Check the audience and distribution channel.
2. Remove anything the participant would not want forwarded.
3. Avoid confidential company information in business challenges.
4. Share NEO scores only when participation is genuinely voluntary.
5. Do not infer mental health, job fitness, or performance from these scores.

## Deleting local data

Use **Clear saved data** inside the app. Clearing site data in browser settings will also remove the saved profile.


