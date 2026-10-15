# Curefoods call audio

Recordings that Plivo plays when the order-ready customer-call scripts ring a customer.

- One file per brand: `<brand>_message_telephony.wav`. Example: `kk_message_telephony.wav` is Krispy Kreme.
- Format: WAV, 8 kHz, mono, 16-bit, cut to the 300–3400 Hz telephone band.
- The script plays the raw link:
  `https://raw.githubusercontent.com/abhilashbishtwork/curefoods-call-audio/main/<file>`
- To change a recording, replace the file under the same name. Calls pick up the new file immediately; the script doesn't need redeploying.
