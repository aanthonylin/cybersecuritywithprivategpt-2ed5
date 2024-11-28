Latest Logs From Latest Build
==============================

Generated On: 2024-11-28 00:40:07 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/aanthonylin/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-28_00:38:40] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-28_00:38:42] STEP 2: Create topics started

  [INFO 2024-11-28_00:38:53] STEP 2: Completed

  [INFO 2024-11-28_00:38:57] STEP 3: producing data started

  [INFO 2024-11-28_00:38:59] MQTT connection established...

  [INFO 2024-11-28_00:38:59] STEP 4: Preprocessing started

  [INFO 2024-11-28_00:39:01] STEP 4: Preprocessing started

  [INFO 2024-11-28_00:39:01] STEP 7: Visualization started

  [INFO 2024-11-28_00:39:08] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-28_00:39:16] STEP 8: Starting docker push for: aanthonylin/cybersecuritywithprivategpt-2ed5-amd64

  [INFO 2024-11-28_00:39:20] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-28_00:39:25] STEP 9: Starting privateGPT

  [INFO 2024-11-28_00:39:39] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 521b05b03efd aanthonylin/cybersecuritywithprivategpt-2ed5-amd64 - message=0

  [INFO 2024-11-28_00:39:45] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [WARN 2024-11-28_00:39:59] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push aanthonylin/cybersecuritywithprivategpt-2ed5-amd64 - message=1

  [INFO 2024-11-28_00:40:07] STEP 10: Started to build the documentation

  [INFO 2024-11-28_00:40:07] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


