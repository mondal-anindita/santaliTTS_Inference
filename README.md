# santaliTTS_Inference

Please download model checkpoints and run a script to perform inference.


## 1. **Download and Organize Checkpoints**

   Download the required checkpoints from the provided link and place them in the `checkpoints` folder in the main project directory:

   1. **Download the checkpoints:**
      - [Download Link](https://iiitaphyd-my.sharepoint.com/:f:/g/personal/anindita_mondal_research_iiit_ac_in/Etc-p1gSu8pFrAekiw8gWQEBlDhrY4Gysdn6FSkXc_ndLQ?e=GkheZg) <!-- Replace # with the actual download link -->

   2. **Create a `checkpoints` folder:**

      Open your terminal and run the following command in the main project directory:

      ```bash
      mkdir checkpoints
      ```

   3. **Move the checkpoints:**

      After downloading, move the checkpoint files into the newly created `checkpoints` folder.

## 2. **Run the Inference Script**

   To run the inference script, follow these steps:

   1. **Navigate to the inference directory:**

      Change to the `inference` directory:

      ```bash
      cd scripts/inference/
      ```

   2. **Run the inference script:**
      To infer, please edit the parameters in scripts/inference/infer.sh file and set the text to the text variable.
      Once you're in the correct directory, run the following command to start the inference process:

      ```bash
      bash infer.sh
      ```




