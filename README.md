# GPT4V : Vision API

소스코드 다운로드

    git clone https://github.com/evadelzz1/llm-GPT4V.git


python 버젼 고정

    cd ./llm-GPT4V

    pyenv versions

    pyenv local 3.11.6

    pyenv versions

python 가상환경 activate 및 필요한 라이브러리 설치

    python3 -m venv .venv

    source .venv/bin/activate

    python3 -V

    pip3 install -r requirements.txt

    echo 'OPENAI_API_KEY="sk-9jz...."' >> .env

예제코드 테스트

    app_0x : colab : app_01colab_GPT4V_DALLE3_PG.ipynb

    app_1x :
        python3 app_10Image.py
        python3 app_11Image2Text.py
        python3 app_12CompareImage.py

    app_2x :
        python3 app_21DataExtract_localImage.py
        python3 app_22DataExtract_imageurl.py

    app_3x : colab : app_31colabVision_API_Tutorial.ipynb

    app_4x :
        python3 app_41Vision_crawl.py

    app_5x :
        python3 -m streamlit run app_51AnalyzeImages.py
        python3 -m streamlit run app_52SketchToPrototype.py

    app_6x :
        python3 app_61narrating_video.py
        python3 app_62website_description.py
        python3 app_63website_comparison.py

        python3 app_65VideoVoice.py
        python3 -m streamlit run app_66VideoVoice.py
        python3 -m streamlit run app_67voiceFromVideo.py


python 가상환경 deactivate

    deactivate

Reference

    OpenAI API DALL-E 3, GPT-4 Vision & GPT-4 Turbo Tutorial (+ Code Examples)
        * [Youtube] (https://www.youtube.com/watch?v=_F9RSESOdDE)
        * [Github]  (https://github.com/krisograbek/openai-notebooks/blob/main/GPT4V-DALLE3-PG.ipynb)
        * File :
            app_01colab_GPT4V_DALLE3_PG.ipynb

    이미지를 이해하고 답변해주는 GPT-4 비전 API 기초 사용법
        * [Youtube] (https://www.youtube.com/watch?v=XzO58yCPQ5E)
        * File :
            app_10Image.py
            app_11Image2Text.py
            app_12CompareImage.py

    NEW GPT-4 Vision API: Best Way to Copy Text from Image (OCR in Python)
        * [Youtube] (https://www.youtube.com/watch?v=dhYumF7SQdA)
        * [Github]  (https://github.com/AI-Unleashed/GPT4V_TextExtract)
        * File :
            app_21DataExtract_localImage.py
            app_22DataExtract_imageurl.py

    Build an AI Image Captioning App With GPT-4 Vision API in 3 Min
        * [Youtube] (https://www.youtube.com/watch?v=-ETwGfjt5ow)
        * [colab]   (https://colab.research.google.com/drive/1nnr0XXwUos0AZV6lNhWuhufBXk0nHVr2#scrollTo=NOcytZ7u2WF-)
        * File :
            app_31colabVision_API_Tutorial.ipynb

    GPT-4 Vision API + Puppeteer = Easy Web Scraping
        * [Youtube] (https://www.youtube.com/watch?v=VeQR17k7fiU)
        * [Github]  (https://github.com/unconv/gpt4v-browsing)
        * File :
            app_41Vision_crawl.py

    How to Build App with OpenAI's New GPT-4 TURBO VISION API (gpt vision)
        * [Youtube] (https://www.youtube.com/watch?v=rnXK2rMlqGo)
        * File :
            app_51AnalyzeImages.py

    # Generate Apps from Sketches or Screenshots with OpenAI GPT-4 Vision API (6 mins quick demo)
        * [Youtube] (https://www.youtube.com/watch?v=ZPe8isJWikQ)
        * File :
            app_52SketchToPrototype.py

    # GPT 4 vision and speech code examples
        * [Youtube] (https://www.youtube.com/watch?v=s54tfEkIXc0)
        * File :
            app_61narrating_video.py
            app_62website_description.py
            app_63website_comparison.py

    # AI Football Commentator ⚽ GPT-4 Vision & TTS in Action
        * [Youtube] (https://www.youtube.com/watch?v=u56K4dL20gA)
        * [Source]  (https://mer.vin/2023/11/gpt-4-vision-adding-football-commentator-to-video/)
        * File :
            app_65VideoVoice.py

    How to use New OpenAI DevDay features - GPT4V x TTS demo tutorial
        * [Youtube] (https://www.youtube.com/watch?v=ymGQkp_C1t0)
        * [Github]  (https://github.com/JayZeeDesign/openai-experiments)
        * File :
            app_66VideoVoice.py

    # Building Web Apps with GPT-4 Vision & Text to Speech (TTS) API - Transform Videos into AI Voiceovers
        * [Youtube] (https://www.youtube.com/watch?v=GAZmtAByzjY&list=PLqQrRCH56DH8JSoGC3hsciV-dQhgFGS1K)
        * [Github]  (https://github.com/avrabyt/GPT4-turbo-with-vision-demo)
        * File :
            app_67voiceFromVideo.py


[![Youtube](https://img.icons8.com/?size=20&id=9itS6I2x2vV2&format=png)](https://www.youtube.com/watch?v=GAZmtAByzjY&list=PLqQrRCH56DH8JSoGC3hsciV-dQhgFGS1K)
[![Github](https://img.icons8.com/?size=20&id=62856&format=png)](https://github.com/avrabyt/GPT4-turbo-with-vision-demo)
