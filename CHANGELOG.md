# Changelog

## 0.1.1

- Publish now returns the status `publishing` instead of `scheduled`. Read the final status with Post: Get.
- The account list no longer fails when n8n requests it before the credential is attached to a new node.

## 0.1.0

First release.

- Publora node: Post (Create, Delete, Get, Get Many, Update), Media (Upload), Account (Get Many). Usable as an AI agent tool.
- Publora Trigger: post published, scheduled, failed, or moved back to draft. Subscribes on activation, unsubscribes on deactivation, verifies the HMAC signature of every event.
