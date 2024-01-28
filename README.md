<h1>CIFAKE-AI-Image-Detector</h1>

<p>A good amount of commentary is already present towards the end of the jupyter file. However I will give some context that is not presented there.</p>

<br />
<br />

<p>This small project was the construction of a CNN with about 45 million parameters, trained on the recent CIFAKE dataset which includes the original CIFAR-10 dataset plus the equivalent fake versions of the real images that were generated by AI.</p>

<br />
<br />

<p>I compared using dropout for this task versus not using dropout and found there to be basically negligible difference (although dropout is a very effective regularizer, just not in this specific case). I provide more takeaways at the very end of the jupyter file.</p>

<br />
<br />

<p>I would like to extend this project to something of greater magnitude, specifically, I would like to train a model to be able to differentiate between real images and those that can be found on Leonardo AI: https://app.leonardo.ai/ . I have not used Midjourney in about a year so I am not able to give a very precise comparison of the quality of images produced using Midjourney versus those produced through, however I must comment that the images that can be generated on Leonardo AI are remarkably impressive in image quality and realism (possibly superior to Midjourney, but again I am not in a position to give a good comparison).</p>
