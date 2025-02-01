# DeepFace-Framework
This project demonstrates the use of the DeepFace library for facial recognition and analysis in Python. It covers three main functionalities:

    Face Verification: Compares two images to determine if they belong to the same person.
    Face Search: Finds the closest matching face from a given database.
    Face Analysis: Extracts attributes like age, gender, emotion, and race from an image.

Requirements:

    Install DeepFace using - !pip install deepface

Face Verification:

result = DeepFace.verify(img1_path="path/to/image1.jpg", img2_path="path/to/image2.jpg")
print(result)

Face Search:

result = DeepFace.find(img_path="path/to/test.jpg", db_path="path/to/database")
print(result)

Face Analysis:

    result = DeepFace.analyze(img_path="path/to/image.jpg")
    print(result)

This script allows users to perform face matching, identification, and analysis efficiently.
