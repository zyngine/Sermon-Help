# SermonNotes AI

SermonNotes AI is a sermon recording and transcription app with AI-powered note generation, keyword highlighting, and integrated Bible study features.

## Components
- **Backend**: Python + FastAPI (deployed to Render)
- **Frontend**: SwiftUI (iOS) + Kotlin (Android)
- **Database**: Firebase or PostgreSQL (optional)
- **File Storage**: AWS S3 or Firebase Storage

## Deployment
1. Push repo to GitHub.
2. Deploy backend via Render (add OPENAI_API_KEY env var).
3. Update API URL in mobile frontend.
4. Publish iOS via Xcode (App Store) and Android via Google Play Console.
