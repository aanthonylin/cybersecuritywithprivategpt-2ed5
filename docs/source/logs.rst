Latest Logs From Latest Build
==============================

Generated On: 2024-11-29 01:53:35 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/aanthonylin/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-29_01:50:24] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-29_01:50:26] STEP 2: Create topics started

  [INFO 2024-11-29_01:50:37] STEP 2: Completed

  [INFO 2024-11-29_01:50:42] STEP 3: producing data started

  [INFO 2024-11-29_01:50:44] MQTT connection established...

  [INFO 2024-11-29_01:50:44] STEP 4: Preprocessing started

  [INFO 2024-11-29_01:50:46] STEP 4: Preprocessing started

  [INFO 2024-11-29_01:50:46] STEP 7: Visualization started

  [INFO 2024-11-29_01:50:52] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-29_01:51:00] STEP 8: Starting docker push for: aanthonylin/cybersecuritywithprivategpt-2ed5-amd64

  [INFO 2024-11-29_01:51:01] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-29_01:51:06] STEP 9: Starting privateGPT

  [INFO 2024-11-29_01:51:15] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-29_01:51:22] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 37e1c3d6f567 aanthonylin/cybersecuritywithprivategpt-2ed5-amd64 - message=0

  [INFO 2024-11-29_01:53:30] STEP 8: Successfully ran Docker push: docker push aanthonylin/cybersecuritywithprivategpt-2ed5-amd64 - message=0

  [INFO 2024-11-29_01:53:35] STEP 10: Started to build the documentation

  [INFO 2024-11-29_01:53:36] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


