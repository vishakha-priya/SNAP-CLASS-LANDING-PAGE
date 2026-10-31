## Snap Class

## LIVE WEBSITE DEMO 
[[https://snap-class-landing-page-chi.vercel.app/](https://snap-class-landing-page-chi.vercel.app/)]

SnapClass is an AI-powered attendance management system that automates classroom attendance using facial recognition and voice recognition. 
The platform provides a web interface for teachers and students,
enabling quick login , attendance marking, subject management, and attendance tracking.

## Teacher's Features
1.Secure teacher authentication
2.Create and manage subjects
3.Generate QR codes for subject enrollment
4.Photo-based attendance using AI facial recognition
5.Voice-based attendance using speaker recognition
6.View and download  attendance records

## Student's Features 
1. Face enrollment
2. Voice enrollment
3. Join subjects using QR code or subject code
4. View attendance history
5. Access enrolled subjects

## Face Attendance
1. Detects faces from classroom images using Dlib.
2. Extracts 128-dimensional facial embeddings.
3. Compares facial embeddings with registered students.
4. Automatically marks attendance for recognized students.

## Voice Attendance
1. Processes audio recordings using Librosa.
2. Extracts speaker embeddings with Resemblyzer.
3. Compares voice embeddings with enrolled students voice .
4. Automatically marks attendance for recognized students.

Tools and Technologies used: Scikit-learn(classification),Dlib(face-recognition),Supabase(postgre SQL database),
                            Librosa(voice loading and preprocessing),Resemblyzer(creates voice embedding),
                            streamlit,HTML,CSS,Flask,Python,Segno(generate QR code)
