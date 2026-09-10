# Vision

카메라 기반 물체 위치 추정 코드를 정리할 위치입니다.

현재 연구 흐름:

```text
Camera calibration / undistortion
→ Background subtraction
→ Rectangle candidates
→ Geometry + physical-size scoring
→ Homography
→ Robot XY
→ Multi-candidate tracking / stability
```

대표 파일로 `cube_xy_geometry_web.py`를 정리해 추가할 예정입니다.

향후 실제 환경 robustness를 검증한 뒤 필요하면 segmentation 기반 인식을 결합합니다.
