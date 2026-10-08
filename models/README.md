Własny detektor grzybów (YOLO11n, wejście 416×416).

- `grzyb-yolo.onnx` – model dla przeglądarki; radar (`radar.html`) sam go wykrywa i używa zamiast CLIP.
- `grzyb-yolo.pt` – pełne wagi; od nich startuje kolejne douczanie w notatniku `trening/grzybowa_mapa_yolo.ipynb`.

Wersja 1 (8.10.2026): Open Images V7 (klasa Mushroom + tło), mAP50 0,64, precyzja 0,66, czułość 0,58.
