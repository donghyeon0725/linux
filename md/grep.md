📌 grep 명령어
-
| /   | grep 사용 예시   | 명령어 옵션                 |
|-----|---|------------------------|
| 1   | 대상 파일에서 문자열 검색 | grep "Lorem" [file]    |
| 2   | 현재 디렉토리에서 모든 파일의 문자열 검색 | grep "Lorem" *         | 
| 3   | 특정 확장자 파일에서 문자열 검색 | grep "Lorem" *.txt     | 
| 4   | 대소문자 구분 없이 검색 | grep -i "lorem" [file] | 
| 5   | 특정 패턴이 없는 문자열 검색 | grep -v Lorem [file]   | 
| 6   | 단어 단위로 검색 | grep -w Lorem [file] |
| 7   | 검색 문자열이 포함된 라인번호 함께 출력 | grep -n Lorem [file] |
| 8   | 하위 디렉토리를 모두 포함한 모든 파일에서 검색 | grep -r Lorem * |
| 9   | 최대 검색 결과 라인수 제한 | grep -m 1 Lorem [file] | 
| 10  | 정규 표현식이 아닌, 문자로 검색 | grep -F "*" [file] | 
| 11  | 검색 결과 앞에 파일 이름 표기 | grep -H Lorem [file] | 
| 12  | 특정 문자로 시작해서, 특정 문자로 끝나는 문자 검색 | grep "L*m" [file] |
| 13  | 문자 + 특정 숫자 패턴 찾기 | grep "[0-9]s" lorem.txt |
| 14  | 정규 표현식, 일반 문자로 취급하기 | grep "\*" [file] |
| 15  | 특정 문자열로 시작하는 패턴 검색 | grep "^Lo" [file] | 
| 16  | 특정 문자열로 끝나는 패턴 검색 | grep "$sum" [file] |
