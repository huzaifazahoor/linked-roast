# LinkedIn Roast

A brutally honest LinkedIn profile auditor powered by Claude AI.

Live at: `https://huzaifazahoor.github.io/linked-roast`

Upload your LinkedIn profile screenshot and PDF export. Get a sharp, direct critique of every section. No sugarcoating. No motivational fluff. Just what is actually wrong with your profile.

## What It Does

- Roasts every section of your LinkedIn profile
- Rates each problem by severity
- Gives an overall profile score out of 10
- Suggests specific improvements after the roast
- Lets you add your own context so the AI does not miss the human side
- Copy your full report as Markdown

## How to Use

**Step 1 - Export your LinkedIn profile**
Go to your LinkedIn profile. Click the More button. Click Save to PDF.

**Step 2 - Take a screenshot**
Screenshot your full LinkedIn profile page. You can upload multiple screenshots.

**Step 3 - Upload and roast**
Go to the live site. Upload your files. Click Roast My Profile.

**Step 4 - Get suggestions**
After the roast loads, scroll to Suggest Me Changes. Add any personal context you want. Click Get Improvement Suggestions.

## API Key

The app works out of the box with no setup needed.

If you want to use your own Anthropic API key, click Add your key at the top of the page and paste it in. Your key is used only in your browser. It is never sent to any server other than Anthropic directly.

Get your API key at: https://console.anthropic.com

## Privacy

- No data is stored anywhere
- No backend server
- Your files go directly from your browser to the Anthropic API
- Nothing is logged or saved

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- Anthropic Claude API
- Single file. No frameworks. No build step. No backend.

## Local Development

Clone the repo and open the file directly in a browser. No server or install needed.
```bash
git clone https://github.com/huzaifazahoor/linked-roast.git
cd linkedin-roast
open index.html
```

## Deployment

This project is deployed as a static site on GitHub Pages.

To deploy your own copy:
1. Fork this repo
2. Go to Settings > Pages
3. Set source to main branch
4. Your site will be live at `https://huzaifazahoor.github.io/linked-roast`

## Contributing

Pull requests are welcome. If you find a bug or want to suggest a feature, open an issue.

## License

MIT
