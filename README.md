Submission Date: May 02, 2020
----------------

Team Members:
-------------

	- Barani Kumar Kalangal Ramasamy Soundararajan
	- Akash Reddy 
	- Preethi Krishnamoorthy Ramesh Kumar

Final Project: Investigate the misalignment between Point Cloud and perspective image 
----------------------------------------

Requirement:
    Add front.jpg, back.jpg, right.jpg, left.jpg, final_project_point_cloud.fuse, trajectory.fuse, camera.config to the same folder as alignment_point.py program

Output Files Generated:
	1. Point Cloud Image Files - front.png, back.png, left.png, right.png
	2. Matching Image Files - front_face.obj, back_face.obj, left_face.obj, right_face.obj, pointcloud_file.obj, enu_file.obj, camera_file.obj

Execution:
	python alignment_points.py


TO RUN USING DOCKER[Optional]:

1. Build image: `docker build .`
2. Run image: `docker run -it -v $(pwd):/app bash`
3. `cd /app` to get to the project inside the running container.
4. Proceed with execution of the program
