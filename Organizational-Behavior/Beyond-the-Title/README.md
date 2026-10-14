# Beyond the Title — Professional Connection Cards

**A privacy-conscious networking card for learning cohorts, workshops, and professional events.**

Introductions in specialized programs often stop at a name and job title. That makes it harder to discover shared experience, complementary expertise, or a useful conversation starter during the first sessions.

Beyond the Title — Professional Connection Cards turns a short self-introduction into a clear, shareable landscape card. Participants can add their professional context, industry journey, current focus, business challenges, and—only if they choose—their NEO Five-Factor scores.

## Classroom context

The first version was developed after an Organizational Behavior session in the EMBA program taught by **Dr. Masoud Shadnam**. The class discussed individual differences in organizations through the internal perspective, with personality as one lens. Participants completed the NEO assessment, creating an opportunity to explore how a cohort could introduce itself and network more intentionally.

This is an independent student project. It is not an official course tool and does not represent Dr. Shadnam or the program.

## What the tool does

- Builds a live professional introduction card in the browser.
- Supports English and Persian card output.
- Captures a professional journey, current focus, and up to three business challenges.
- Draws an optional Five-Factor radar chart from user-entered NEO scores.
- Lets the user hide all NEO interpretation while still showing the chart.
- Downloads the card as a high-resolution PNG for sharing.
- Stores form data locally in the browser; it has no backend.

## Quick start

### Online

Open the GitHub Pages link for this repository, choose **Beyond the Title**, complete only the fields you want to share, and select **Download PNG**.

### Locally

1. Download this folder or clone the repository.
2. Open `index.html` in a current version of Chrome, Edge, Firefox, or Safari.
3. Complete the form.
4. Review the card and download the PNG.

No build step is required. The PNG renderer is loaded from cdnjs; the rest of the application is self-contained.

## NEO: scope and responsible use

NEO instruments measure five broad personality domains commonly summarized as Neuroticism, Extraversion, Openness, Agreeableness, and Conscientiousness. In this project, scores are entered by the participant and used only to generate a personal visual and optional conversation prompts.

Important boundaries:

- This tool does **not** administer, score, validate, or diagnose a NEO assessment.
- Score meaning depends on the specific instrument, norms, language, and qualified interpretation.
- The generated observations are simplified prompts, not psychological advice.
- Do not use the card for recruitment, promotion, performance evaluation, or other high-stakes decisions.
- Sharing personality information should always be voluntary.

## Privacy

The app has no server and does not submit form values anywhere. Data is saved in the browser's local storage so the form can be restored on the same device. The user can clear it at any time with **Clear saved data**.

The page loads the `html2canvas` library from cdnjs to create the PNG. That request can reveal ordinary connection metadata to the CDN, but the form values are not included in it. See [PRIVACY.md](PRIVACY.md) for the full explanation and safe-use checklist.

## Ali Zahrawi starter profile

The file [`examples/ali-zahrawi-profile.json`](examples/ali-zahrawi-profile.json) is an editable reference template. It is intentionally conservative: it contains Ali's name and public GitHub profile only. Employer, role, contact details, industry history, business challenges, and NEO scores are blank because they were not verified.

Use it as a checklist while completing the web form, and replace the blanks only with accurate information you are comfortable sharing.

## Customization

The project is a single HTML file. Common edits:

- Change colors in the CSS variables near the top of `index.html`.
- Edit the bilingual labels in the `COPY` object.
- Adjust the guidance text in each input's placeholder.
- Remove the NEO section if the context does not make personality sharing appropriate.

## Suggested facilitation flow

1. Explain why the cards are being used and make every field optional.
2. Give participants 5–7 minutes to create and review their cards.
3. Ask each person to share only what they are comfortable disclosing.
4. Pair people around a shared challenge or complementary experience.
5. Remind everyone not to redistribute cards outside the group without consent.

## Credits

Concept and implementation by [Ali Zahrawi](https://github.com/alizahrawi).


