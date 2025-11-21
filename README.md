
def main():
    # int
    age = 25
    print(f'Integer: {age}')

    # float
    height = 5.9
    print(f'Double: {height}')

    # str
    name = 'Nokuthula'
    print(f'String: {name}')

    # bool
    is_student = True
    print(f'Boolean: {is_student}')

    # list[int]
    numbers = [1, 2, 3, 4, 5]
    print(f'List[int]: {numbers}')


# Convert String to int
def string_to_int(s: str) -> int:
    return int(s)


# Convert String to float
def string_to_float(s: str) -> float:
    return float(s)


# Convert int to String
def int_to_string(n: int) -> str:
    return str(n)


# Convert float to String
def float_to_string(n: float) -> str:
    return str(n)


def convert_and_display(number: str):
    int_value = int(number)
    float_value = float(number)

    print(f'Integer value: {int_value}')
    print(f'Double value: {float_value}')


if __name__ == '__main__':
    main()
    # Test the function
    convert_and_display('42')
 
