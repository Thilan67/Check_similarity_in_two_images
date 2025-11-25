# Check similarity in two images
###### This project check the similarity of two images using structural (brightness, contrast, structure), color, Mean square error (Pixel-by-pixel differences) and feature similarity (matching keypoints). 

## How to run
#### 1)Get your ngrok Token 
######       Go to https://ngrok.com
######       Sign up for free
######      Copy your token from the dashboard

#### 2)Open Google Colab and click Run all
#### 3)Enter your ngrok token
#### 4)Open Browser
###### Go to https://e2fb2ec51ada.ngrok-free.app -> http://localhost:5000
#### 5) Upload your two photos 
#### 6) Click "Check Similarity"

# Sample Output
###### Structural Similarity Index (SSIM): 0.5032
###### Pixel Difference (MSE): 103.38
###### Color Similarity Score: 0.9294
###### Feature-based Similarity: 133


## 1. Structural Similarity Index (SSIM): 0.5032

Scale: 0 to 1

###### 1.0 = exactly same 
###### 0.8–1.0 = very similar 
###### 0.5–0.8 = somewhat similar
###### < 0.5 = not similar


## 2. Mean Squared Error (MSE): 103.38

Interpretation:

###### 0 = no difference
###### Higher = more difference

## 3. Color Similarity Score: 0.9294
(Usually histogram correlation)

Scale: -1 to 1

###### 1.0 = color distribution same
###### 0.7–1.0 = similar colors
###### 0.5–0.7 = moderate
###### < 0.5 = not similar

## 4. Feature-based Similarity: 133 matches
(ORB/SIFT keypoints)

Interpretation:
###### 0–20 = not similar
###### 20–50 = maybe small similarity
###### 50–100 = moderate
###### 100+ = high similarity
