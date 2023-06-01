•Team Introduction
  –정재민 202211371
  
•Topic Introduction
  –'human pose' topic 범주 내에 있는 주제이다. 사진 속 사람의 자세를 파악하고 골격을 중심으로 human shape를 형성하는 deeplearning program이다.
  
•Results
  –Describe the representative results or findings (currently empty)
  
  
![스크린샷 2023-06-01 233709](https://github.com/jeongjam/opensw23-JJM/assets/105273819/a08c566f-5912-4d7f-bd73-8c70509c414f)

![스크린샷 2023-06-01 233717](https://github.com/jeongjam/opensw23-JJM/assets/105273819/808f9920-6d51-4a23-8f72-5d5ce876fb26)

•Analysis/Visualization
  –Present any analysis or visualizations related to the topic (currently empty)

•Installation
  –reference: 작성자는 windows11, 64bit운영체제, 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 2.80 GHz 프로세서를 가진 노트북으로 수행하였다.  
  1. pytorch 1.2이상의 버전을 설치한다. (download link: https://pytorch.org/)
  2. python의 버전은 3.7.2이상이어야 한다.
  3. SMPL을 준비한다.
  
  3-1. cmd 가상개발환경에 접속한다.
  
  3-2. pip install smplpytorch 명령어를 이용한다.
  
  4. requirements를 수행한다.
  
  4-1. pip install opencv-python
  
       pip install transforms3d
       
       pip install pycocotools
       
       pip install git+https://github.com/scottandrews/chumpy.git@fe51783e0364bf1e9b705541e7d77f894dd2b1ac
       
       pip install pyrender
       
       pip install trimesh
       
       pip install pyyaml
       
       pip install easydict
       
       pip install tqdm 
       
       명령어들을 순서대로 수행한다.
       
  5. python demo/run.py --gpu 0 --input_pose demo/h36m_joint_input.npy --joint_set human36 와 같은 명령어로 inference를 수행한다.
  
  5-1. demo/h36m_joint_input.npy 대신 다른 .npy파일을 사용해도 좋다.

•Presentation
  –Insert the video link for the final presentation (currently empty)
