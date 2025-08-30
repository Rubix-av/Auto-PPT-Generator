📖 Usage Guide
Step 1: Configure LLM Provider

Choose from OpenAI, Anthropic, or Google Gemini
Enter your API key (never stored or logged)
API keys are used only for content analysis

Step 2: Upload Template

Upload a PowerPoint template (.pptx or .potx)
The app will extract colors, fonts, and layouts
Images from the template will be preserved and reused

Step 3: Enter Content

Paste your text, markdown, or prose
Optionally add guidance (e.g., "investor pitch deck")
Use sample content for testing

Step 4: Generate

Click "Generate Presentation"
Monitor progress through the status indicators
Download your styled presentation automatically

🔧 API Keys Setup
OpenAI

Visit OpenAI API
Create a new API key
Ensure you have credits available

Anthropic (Claude)

Visit Anthropic Console
Generate an API key
Check your usage limits

Google Gemini

Visit Google AI Studio
Create an API key
Enable the Generative AI API

🛠 Technical Details
Architecture

Frontend: Pure HTML, CSS, JavaScript
PowerPoint Processing: JSZip library for .pptx manipulation
LLM Integration: REST API calls to various providers
File Handling: Client-side processing only

Key Libraries

JSZip: PowerPoint file manipulation
XML2JS: XML parsing for PowerPoint structure
Native APIs: Fetch, Blob, URL for file handling

Browser Compatibility

Chrome 80+
Firefox 75+
Safari 13+
Edge 80+

🔒 Security & Privacy

No Data Storage: All processing happens in your browser
API Keys: Never stored, logged, or transmitted to our servers
Client-Side Only: No backend servers or databases
CORS Compliant: Direct API calls to LLM providers

🎯 Use Cases

Business Presentations: Convert reports into slide decks
Educational Content: Transform lectures into visual presentations
Sales Materials: Create pitch decks from product descriptions
Research Summaries: Turn papers into presentation format
Meeting Notes: Convert discussions into actionable slides

🔍 Troubleshooting
Common Issues
"API call failed"

Verify your API key is correct and active
Check if you have sufficient credits/quota
Ensure stable internet connection

"Template parsing error"

Use valid PowerPoint files (.pptx or .potx)
File size should be under 10MB
Avoid corrupted or password-protected files

"No slides generated"

Ensure text input is substantial (50+ words recommended)
Check if LLM provider is responding correctly
Try with sample content first

Browser Issues

Enable JavaScript
Allow downloads in browser settings
Clear cache if experiencing issues
Use incognito mode to test
