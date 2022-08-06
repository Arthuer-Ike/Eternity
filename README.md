# Eternity
import argparse

parser = argparse.ArgumentParser(description='')
parser.add_argument('integers', type=str, nargs='+',help='')
args = parser.parse_args()

print(args.integers)
#integers为参数的位置参数
#nargs是用来说明传入的参数个数，'+' 表示传入至少一个参数
