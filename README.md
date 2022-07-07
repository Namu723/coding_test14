#나누어 떨어지는 숫자 배열


def solution(arr, divisor):
    answer = []
    for i in arr:
        if i % divisor == 0:
            answer.append(i)
        if answer == []:
            return -1
    return answer

#print(solution([5, 9, 7, 10]	,5))
#ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ


def solution(arr, divisor):
    return sorted([n for n in arr if n%divisor == 0]) or [-1]
