# sorting_algorithm.py

def bubble_sort(arr):
    n = len(arr)

    for i in range(n - 1):
        for j in range(n - 1 - i):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

    return arr

# Example usage
numbers = [5, 2, 9, 1, 7]
sorted_numbers = bubble_sort(numbers)
print(sorted_numbers)
