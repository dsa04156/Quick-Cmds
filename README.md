# Quick-Cmds

**Quick-Cmds**는 Kubernetes와 Ubuntu 명령어의 유용한 단축키 및 팁을 모아둔 레포지토리입니다. 자주 사용하는 명령어를 빠르게 찾고 기억할 수 있도록 돕기 위해 설계되었습니다.

## 설정 방법

이 레포지토리의 설정을 위해 아래의 내용을 `.bashrc` 또는 `.bash_profile` 파일에 추가하세요.

```bash
vi ~/.bashrc
```
입력후
```bash
source ~/.bashrc
```

### 설명 및 사용법

1. **`cd` 함수**:
   - 디렉토리 변경 후 자동으로 현재 디렉토리의 내용을 리스트로 보여줍니다.
   - 사용 예시:
     ```bash
     cd /path/to/directory
     ```

2. **Alias 목록**:
   - **`..`**: 상위 디렉토리로 이동합니다.
     ```bash
     ..
     ```
   - **`...`**: 두 단계 상위 디렉토리로 이동합니다.
     ```bash
     ...
     ```
   - **`h`**: 최근 명령어를 조회합니다.
     ```bash
     h
     ```


### Kubernetes

- **`k`**: `kubectl`의 약어
- **`kg`**: `kubectl get` - 리소스 조회
- **`kga`**: `kubectl get all` - 현재 네임스페이스의 모든 리소스 조회
- **`kd`**: `kubectl describe` - 리소스에 대한 자세한 정보 조회
- **`kf`**: `kubectl apply -f` - YAML 파일을 사용하여 리소스 적용
- **`kx`**: `kubectl exec -it` - 파드에서 명령어 실행
- **`kr`**: `kubectl rollout` - 배포 롤아웃 관리
- **`ks`**: `kubectl get services` - 서비스 목록 조회
- **`ksc`**: `kubectl get configmaps` - ConfigMap 목록 조회
