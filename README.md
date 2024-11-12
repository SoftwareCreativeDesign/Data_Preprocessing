# Data_Preprocessing

Nor/Mal : 정상(Normal)과 비정상(Abnormal)을 나타내는 값
has_ip: URL에 IP 주소가 포함되어 있는지 여부 (예: http://125.98.3.123/fake.html)
long_url: URL 길이를 나타내는 값
is_shortened: URL이 TinyURL과 같은 URL 축소 서비스를 통해 짧아졌는지 여부
has_at_symbol: URL에 "@(At)" 기호가 포함되어 있는지 여부
has_double_slash: URL 경로에 "//(double slash)" 기호가 포함되어 있는지 여부 ("//"는 리다이렉션을 유도할 가능성이 있음)
has_dash: URL의 도메인에 "-(Dash)" 기호가 포함되어 있는지 여부
subdomain_count: 서브도메인의 개수를 나타냄
is_https: URL이 https로 시작되는지 여부
domain_reg_length: 도메인 등록 기간을 나타냄 (확인 불가능한 값)
has_favicon: 파비콘(Favicon)이 URL의 도메인과 다른 도메인에서 로드되었는지 여부
non_standard_port: 비표준 포트를 사용하는지 여부
