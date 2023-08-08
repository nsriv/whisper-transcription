# whisper-transcription
A Google Colab implementation of OpenAI's Whisper
<a target="_blank" href="https://colab.research.google.com/github/nsriv/whisper-transcription/blob/main/Whisper_Transcription.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

##  About
This Colab Notebook is designed to transcribe a given audio file, of any language, into text. To accomplish this, it uses the code contained in this notebook, which leverages open-source and free of cost Python packages and machine learning models. The transcription of the audio file is contained within the Google Drive account mounted in the section on "Saving," and upon exit of the runtime, all uploaded data is permanently deleted, thus not compromising user or patient privacy.

This notebook runs in a 'runtime environment' on a virtual machine hosted on the Google Cloud Platform. This runtime is temporary and destructible, but is connected to a GPU that provides the muscle for the computation. Once the runtime is disconnected, all data except the text output is deleted. No data is sent back to Google except for the resources and running time requested by the code being executed.
