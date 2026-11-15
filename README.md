# Kishore Gowda V - Modern Minimal Portfolio & Contact Backend

A modern, clean, bright, and minimal developer portfolio website built for **Kishore Gowda V**, 19-year-old Computer Science & Engineering (AI & ML) student at **Jain University, Bengaluru**.

---

## 🌟 Highlights & Features

1. **Simple, Bright & Minimal UI/UX**:
   - Modern typography (`Plus Jakarta Sans` & `JetBrains Mono`).
   - Clean professional portrait framing with status pills and tags.
   - Built-in Dark / Bright mode toggle with preference stored in `localStorage`.
   - Responsive mobile drawer and smooth-scroll progress bar.

2. **Personal Profile**:
   - **Name**: Kishore Gowda V
   - **Age & Location**: 19 years old, Bangalore (Bengaluru), Karnataka, India
   - **Education**: B.Tech CSE (Artificial Intelligence & Machine Learning) at Jain University
   - **LinkedIn**: [linkedin.com/in/kishoregowda07](https://www.linkedin.com/in/kishoregowda07)
   - **GitHub**: [github.com/kishoregowda07](https://github.com/kishoregowda07)
   - **Email**: `kishore00007kumar@gmail.com`

3. **Featured Projects**:
   - **Smart Guard Monitor System (SIH 2026)** *(Built & Operational)*:
     - Real-time perimeter monitoring and anomaly detection using computer vision and edge AI.
     - **Live Demo Overview**: [https://si-h-2026.vercel.app/overview](https://si-h-2026.vercel.app/overview)
     - Tech: `Python`, `OpenCV`, `YOLO`, `MQTT`, `FastAPI / Flask`, `Vercel`
   - **Blood Donation Lifeline** *(In Active Development)*:
     - Real-time emergency blood donation platform connecting seekers with voluntary donors based on geographic radius and Rh compatibility.

4. **Beyond Code & Passions**:
   - 🤼 **University Kabaddi Player**: University-level athlete representing Jain University on the mat.
   - ⚽🏉 **Football & Rugby**: Competitive team sports enthusiast.
   - 🏎️ **Motorsports & Speed**: Passionate follower of racing dynamics and performance engineering.
   - ✈️ **Travelling & Exploration**: Road trips, trekking, and discovering new cultures.
   - 📚 **Kannada Literature & Novels**: Deep appreciation for regional heritage and classic Kannada storytelling.

5. **Fully Working Backend**:
   - Standalone Python 3 HTTP + API server (no external pip dependencies).
   - `POST /api/contact` stores submissions in SQLite (`data/contacts.db`) and `data/messages.jsonl`.
   - **Admin Message Portal (`/admin`)**: Private dashboard to view, search, reply to, and manage inquiries (passkey: `kishore2026`).
   - Optional automated Gmail notification via standard SMTP.

---

## 🚀 Running the Server Locally

```bash
python3 backend/server.py
```

- **Portfolio**: [http://localhost:8080](http://localhost:8080)
- **Admin Portal**: [http://localhost:8080/admin](http://localhost:8080/admin) *(Passkey: `kishore2026`)*
