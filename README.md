packages/apps/LineageParts/AndroidManifest.xml
frameworks/base/services/usb/java/com/android/server/usb/UsbDeviceManager.java

android/lineage/lineage-sdk/lineage/lib/main/java/org/lineageos/platform/internal/TrustInterfaceService.java
```
 private boolean postOnBoardingNotification() {
        // String title = mContext.getString(R.string.trust_notification_title_onboarding);
        // String message = mContext.getString(R.string.trust_notification_content_onboarding);
        // Intent intent = new Intent(INTENT_ONBOARDING);
        // intent.setFlags(Intent.FLAG_ACTIVITY_NEW_TASK);
        // PendingIntent pIntent = PendingIntent.getActivity(mContext, 0, intent,
        //     PendingIntent.FLAG_IMMUTABLE);

        // Notification.Builder notification = new Notification.Builder(mContext, TRUST_CHANNEL_ID)
        //         .setContentTitle(title)
        //         .setContentText(message)
        //         .setStyle(new Notification.BigTextStyle().bigText(message))
        //         .setAutoCancel(true)
        //         .setContentIntent(pIntent)
        //         .setSmallIcon(R.drawable.ic_trust)
        //         .extend(new Notification.TvExtender().setChannelId(TRUST_CHANNEL_ID_TV));

        // createNotificationChannelIfNeeded();
        // mNotificationManager.notify(ONBOARDING_NOTIFCATION_ID, notification.build());
        return true;
    }
```
