# Tideways release tragging through github action

## Usage

```yaml
    - uses: halltabak/tideways_release:1.0.0
      with:
        tidways_api_key: ${{ secrets.TIDEWAYS_API_KEY }}
        release_name: "1.35.0-rc1"
        service_name: "app"
        environment: "approval"
```