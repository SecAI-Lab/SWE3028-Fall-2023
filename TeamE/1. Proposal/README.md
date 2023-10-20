# MailGPT-DOC: Dynamic Content Generation for Emails with GPT

Harness the unparalleled capabilities of GPT for email drafting. MailGPT, designed with React, Docker, and AWS guarantees users an intuitive, adaptive, and unmatched emailing experience.

## 📜 Building and Viewing the Documentation

If you're looking to build the provided LaTeX documentation, follow these steps:

### 1️⃣ Navigate:
Head to the directory containing the LaTeX files.

### 2️⃣ Make Commands:

- **Build PDF**: `make`
   - This will compile your LaTeX document into a PDF format.
  
- **View PDF**: `make open`
   - This command will automatically open the generated PDF for you to view.

- **Cleanup**: `make clean`
   - Clear out auxiliary files but keep the PDF.
  
- **Deep Cleanup**: `make deepclean`
   - This will wipe the directory, including the generated PDF.

---

**Note**: The `Makefile` is configured with the assumption that you have `evince` PDF viewer installed. If you are using a different PDF viewer, ensure you modify the `Makefile` accordingly.
