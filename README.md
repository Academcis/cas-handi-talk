<h1>👌 HandiTalk</h1>

<div style="border: 1px solid black; padding: 10px;">

<p>
  This project was developed as part of the <strong>Context Awareness Systems</strong> course on the Master's in Computer Engineering (Mobile Computing) degree during the 2023/24 academic year.
</p>

<h1>Collaborators</h1>
<ul>
  <li><a href="https://github.com/anamsmartins">Ana Martins</a></li>
  <li><a href="https://github.com/ivoafonsobispo">Ivo Bispo</a></li>
  <li><a href="#">João Vieira</a></li>
</ul>

<h1>Project Description</h1>

<p>
<strong>HandiTalk</strong> is an Android application designed to support the learning of American Sign Language (ASL)
through the use of <strong>Artificial Intelligence</strong> and <strong>gesture recognition</strong>.
The application provides real-time feedback on finger positioning, allowing users to practice and improve their signs
in an interactive and engaging way.
</p>

<p>
Inspired by gamified learning platforms such as Duolingo, HandiTalk promotes an enjoyable learning experience by
combining AI-driven evaluation with structured exercises. Users can select letters or common words to learn and
perform the corresponding gestures in front of the camera, receiving immediate feedback on accuracy and correctness.
</p>

<p>
The gesture recognition system is powered by a <strong>custom-built machine learning model</strong> based on
<strong>MediaPipe Google Vision</strong>. A dedicated dataset was created using images captured in diverse environments
and lighting conditions. Each image was manually annotated with hand keypoints using <strong>Roboflow</strong>,
ensuring precise detection of finger positions.
</p>

<p>
By integrating computer vision, machine learning, and mobile development, HandiTalk aims to make sign language
education more accessible, efficient, and inclusive.
</p>

<p>
  <i>Let AI be your hands in learning sign language!</i>
</p>

<h1>Technical Approach</h1>

<h2>Dataset Creation</h2>
<ul>
  <li>36 gesture classes (26 ASL letters + 10 common words)</li>
  <li>Images captured across different backgrounds, distances, and lighting conditions</li>
  <li>Keypoint annotation performed using Roboflow templates</li>
  <li>Dataset exported in COCO format</li>
  <li>Data augmentation (brightness variation, noise injection)</li>
</ul>

<h2>Model Development</h2>
<ul>
  <li>Custom gesture recognition model built with MediaPipe Model Maker</li>
  <li>Training performed using annotated keypoint data</li>
  <li>Model exported as a <code>.task</code> file for Android integration</li>
</ul>

<h2>Android Application</h2>
<ul>
  <li>Developed in <strong>Kotlin</strong></li>
  <li>Based on the MediaPipe Gesture Recognizer Android Demo</li>
  <li>Fragment-based navigation architecture</li>
  <li>Camera-based real-time gesture recognition</li>
</ul>

<h1>Results</h1>

<p>
The final dataset contains <strong>1046 images</strong>, divided into training, validation, and test sets.
Due to the high number of gesture classes and limited samples per class, the trained model achieved an accuracy of
approximately <strong>56–57%</strong>.
</p>

<p>
Despite accuracy limitations, the application successfully demonstrates real-time gesture recognition and provides
a solid foundation for future improvements.
</p>

<h1>Future Work</h1>
<ul>
  <li>Expand the dataset with more gesture samples</li>
  <li>Increase vocabulary and conversational signs</li>
  <li>Integrate facial expression recognition</li>
  <li>Explore 3D landmarks and advanced keypoint models</li>
  <li>Improve overall model accuracy and robustness</li>
</ul>

<h1>Tools & Technologies</h1>
<ul>
  <li>Kotlin – Android application development</li>
  <li>MediaPipe Google Vision – Gesture recognition</li>
  <li>Roboflow – Dataset annotation and preprocessing</li>
  <li>Python – Dataset processing and model training</li>
  <li>Android Studio – Development environment</li>
  <li>Google Colab – Model training environment</li>
</ul>

<h1>Other Information</h1>
<ul>
  <li><strong>Our project received a grade of 15.05 out of 20.</strong></li>
  <li>This project was developed for the <a href="https://www.ipleiria.pt/curso/mestrado-em-engenharia-informatica-computacao-movel/" rel="nofollow">Computer Engineering (Mobile Computing) master's degree</a> at <a href="https://www.ipleiria.pt" rel="nofollow">Polytechnic of Leiria</a></li>
</ul>

<p>
<a href="https://www.ipleiria.pt/estg/" rel="nofollow">
<img src="https://www.ipleiria.pt/normasgraficas/wp-content/uploads/sites/80/2017/09/estg_h-01.jpg"
     width="300"
     alt="Escola Superior de Tecnologia e Gestão"
     style="max-width: 100%;">
</a>
</p>

</div>

