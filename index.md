# Macroboi privacy policy

Effective date: 4 November 2026
Policy URL: https://dennisschmid99-code.github.io/macroboi-privacy/
Contact: dennis.schmid99@gmail.com

Macroboi is a calorie and macro tracker for Android. This policy says what it does with your data.

## The short version

- Your diary, your entries and your progress photos stay on your phone.
- Macroboi has no accounts, no ads and no analytics.
- Data leaves your phone in three cases, and all are your choice: the one-time download of the on-device
  AI model, Gemini, which is off unless you turn it on and add your own key, and feedback you send
  from the "Give feedback" bar.

## Entries, diary and photos

- Your diary, goals, foods, dishes and supplement records are stored in the app's database on your phone.
- What you type or say is read by the on-device AI model (Gemma) on your phone.
- Progress photos are saved in the app's private storage on your phone. Camera access is only needed to
  take them, and the camera is optional.

## Speech

Speech is recognised on your phone. Macroboi uses only the on-device speech recognizer.

## Health Connect

If you connect Health Connect, Macroboi reads these records and never writes to Health Connect: steps,
distance, workouts, active and total calories burned, sleep, heart rate and resting heart rate. It reads
them only while Macroboi is open. They show in the Activity tab and in your diary. Band calories never change
your calorie goal or your energy balance.

Macroboi keeps copies of these records in its database on your phone. Android cloud backup includes that
database (see "Backup and transfer").

## The on-device model

The first time, Macroboi downloads its on-device AI model (about 2.6 GB) from Hugging Face
(huggingface.co). Hugging Face receives the usual details of a download request, such as your IP address.
No diary data is sent for the download. After the download, the model is checked and kept in the app's
private storage.

## Gemini (optional, your own key)

- Gemini is off by default.
- If you turn it on and save your own Gemini key in Settings, each entry you type or say is sent to Google's
  Gemini API. What is sent is the entry text and the instructions Macroboi uses to read it. Your key is sent
  with each request and is stored on your phone.
- Macroboi asks Google not to store these requests. Google's own terms for the Gemini API still apply to
  what Google does with them, so read those terms before you turn Gemini on.
- Saving a key sends one short test request to Google.
- With Gemini off, nothing is sent to Google.

## Feedback (alpha version)

While Macroboi is in testing, a bar at the top says "Alpha version · Give feedback". Nothing is sent
unless you write a message and press Send. Then Macroboi sends, to the developer's Google Form (Google
Forms, run by Google):

- your message, and your name if you type one (optional);
- a random id made for this install, so messages from one phone can be grouped. It is not linked to
  your Google account or your phone number;
- the app version and your phone's model and Android version.

No diary data, photos or Health Connect records are sent. The developer reads the messages in a Google
Sheet. To have a message deleted, email the contact address above with roughly when you sent it.

## Notifications and reminders

If you allow notifications, Macroboi shows supplement reminders at the times you set. The reminders are
alarms on your phone. Macroboi sets them again after a restart.

## Backup and transfer

- Android cloud backup includes only the diary database (macroboi.db). It does not include the AI model or
  the progress photos.
- Transfer from one phone to another also includes the progress photos. It does not include deleted photos
  kept in the app's trash.

## Permissions

- Microphone: speech entry.
- Camera: progress photos (optional).
- Notifications: supplement reminders.
- Internet: the model download, Gemini if you turn it on, and feedback you send.
- Health Connect (read only, optional): the records listed above.
- Vibrate: haptic feedback.
- Network state: checking whether you are online.

## No accounts, ads or analytics

Macroboi has no sign-in and no account. It shows no advertising and contains no analytics or crash-reporting
service. The feedback bar sends only what you write, when you press Send.

## Deleting your data

Uninstalling Macroboi removes its data from your phone. Copies made by Android backup are kept under your
Google account's backup settings.

## Changes

If this policy changes, the new version will be published at the policy URL with a new effective date.
