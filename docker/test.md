cd docker/
docker build --network host -t foundationpose .
bash run_container.sh
bash build_all.sh
python run_demo.py
