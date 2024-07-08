# traffic-detection

    Transit detection is a project that use IA to detect, track and count vehicles
  </p>


https://github.com/tayyib57/Smart_city/blob/main/trafic%20detection.mov

This modified script can count, track, annotate, classify, and distinguish different classes of vehicles.
</div>



## 💻 install


- clone repository and navigate to example directory

    ```bash
    git clone https://github.com/tayyb57/Smart_city.git
cd Smart_city
    ```

- setup python environment and activate it [optional]

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

- install required dependencies

    ```bash
    pip install -r requirements.txt
    ```

- download `model4.pt` and `output.mov` files

    ```bash
    ./setup.sh
    ```

## ⚙️ run

```bash
python script.py \
--source_weights_path data/model4.pt \
--source_video_path data/output.mov \
--confidence_threshold 0.3 \
--iou_threshold 0.5 \
--target_video_path data/output_result.mov
```
