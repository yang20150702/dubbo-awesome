# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.350 ops/ms
# Warmup Iteration   2: 3.116 ops/ms
# Warmup Iteration   3: 6.087 ops/ms
Iteration   1: 6.296 ops/ms
Iteration   2: 6.516 ops/ms
Iteration   3: 6.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.476 ±(99.9%) 2.969 ops/ms [Average]
  (min, avg, max) = (6.296, 6.476, 6.614), stdev = 0.163
  CI (99.9%): [3.506, 9.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.238 ops/ms
# Warmup Iteration   2: 6.205 ops/ms
# Warmup Iteration   3: 6.831 ops/ms
Iteration   1: 6.799 ops/ms
Iteration   2: 7.057 ops/ms
Iteration   3: 7.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.992 ±(99.9%) 3.088 ops/ms [Average]
  (min, avg, max) = (6.799, 6.992, 7.118), stdev = 0.169
  CI (99.9%): [3.904, 10.079] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.988 ops/ms
# Warmup Iteration   2: 5.835 ops/ms
# Warmup Iteration   3: 6.668 ops/ms
Iteration   1: 6.514 ops/ms
Iteration   2: 6.454 ops/ms
Iteration   3: 6.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.547 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (6.454, 6.547, 6.671), stdev = 0.112
  CI (99.9%): [4.506, 8.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 4.658 ops/ms
# Warmup Iteration   3: 5.021 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.166 ops/ms
Iteration   3: 5.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.223 ±(99.9%) 1.765 ops/ms [Average]
  (min, avg, max) = (5.166, 5.223, 5.335), stdev = 0.097
  CI (99.9%): [3.458, 6.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 15.214 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.530 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.007 ms/op
Iteration   1: 4.898 ±(99.9%) 0.011 ms/op
Iteration   2: 4.704 ±(99.9%) 0.016 ms/op
Iteration   3: 4.840 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.814 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (4.704, 4.814, 4.898), stdev = 0.100
  CI (99.9%): [2.999, 6.630] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.569 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.367 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.680 ±(99.9%) 0.007 ms/op
Iteration   1: 4.756 ±(99.9%) 0.007 ms/op
Iteration   2: 4.685 ±(99.9%) 0.011 ms/op
Iteration   3: 4.547 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.662 ±(99.9%) 1.934 ms/op [Average]
  (min, avg, max) = (4.547, 4.662, 4.756), stdev = 0.106
  CI (99.9%): [2.728, 6.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.341 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.343 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.799 ±(99.9%) 0.009 ms/op
Iteration   1: 4.887 ±(99.9%) 0.010 ms/op
Iteration   2: 4.890 ±(99.9%) 0.007 ms/op
Iteration   3: 4.875 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.884 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (4.875, 4.884, 4.890), stdev = 0.008
  CI (99.9%): [4.740, 5.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.749 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.834 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.852 ±(99.9%) 0.011 ms/op
Iteration   1: 5.586 ±(99.9%) 0.014 ms/op
Iteration   2: 6.074 ±(99.9%) 0.008 ms/op
Iteration   3: 6.003 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.888 ±(99.9%) 4.805 ms/op [Average]
  (min, avg, max) = (5.586, 5.888, 6.074), stdev = 0.263
  CI (99.9%): [1.083, 10.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.883 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.019 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.114 ±(99.9%) 0.020 ms/op
Iteration   1: 4.964 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 25.436 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 4.828 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   10.028 ms/op
                 createUser·p0.999:  23.150 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 4.854 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.907 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  21.074 ms/op
                 createUser·p0.9999: 29.865 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 196473
  mean =      4.881 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 133381 
    [ 5.000,  7.500) = 56296 
    [ 7.500, 10.000) = 4496 
    [10.000, 12.500) = 1173 
    [12.500, 15.000) = 381 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.034 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     22.824 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.271 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.120 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.766 ±(99.9%) 0.016 ms/op
Iteration   1: 4.701 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.750 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  22.739 ms/op
                 existUser·p0.9999: 27.630 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.843 ms/op
                 existUser·p0.50:   4.538 ms/op
                 existUser·p0.90:   5.833 ms/op
                 existUser·p0.95:   6.537 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  17.505 ms/op
                 existUser·p0.9999: 25.918 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 4.787 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  25.350 ms/op
                 existUser·p0.9999: 39.277 ms/op
                 existUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 202113
  mean =      4.748 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186 
    [ 2.500,  5.000) = 149442 
    [ 5.000,  7.500) = 46327 
    [ 7.500, 10.000) = 4226 
    [10.000, 12.500) = 1144 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.685 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     23.262 ms/op
     p(99.9900) =     30.531 ms/op
     p(99.9990) =     39.515 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.994 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.746 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.023 ms/op
Iteration   1: 5.184 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   12.780 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 27.415 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   2: 4.997 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  22.218 ms/op
                 getUser·p0.9999: 30.376 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 4.977 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   7.381 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  20.747 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 189984
  mean =      5.051 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 122802 
    [ 5.000,  7.500) = 56637 
    [ 7.500, 10.000) = 7421 
    [10.000, 12.500) = 1835 
    [12.500, 15.000) = 678 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.929 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     30.923 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.197 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.218 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.022 ms/op
Iteration   1: 5.861 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.455 ms/op
                 listUser·p0.999:  24.805 ms/op
                 listUser·p0.9999: 33.008 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 5.816 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 29.017 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   3: 5.637 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   12.395 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166308
  mean =      5.770 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 48567 
    [ 5.000,  7.500) = 103171 
    [ 7.500, 10.000) = 10270 
    [10.000, 12.500) = 2759 
    [12.500, 15.000) = 858 
    [15.000, 17.500) = 321 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     22.076 ms/op
     p(99.9900) =     31.616 ms/op
     p(99.9990) =     33.325 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.476 ± 2.969  ops/ms
ClientPb.existUser                       thrpt       3   6.992 ± 3.088  ops/ms
ClientPb.getUser                         thrpt       3   6.547 ± 2.041  ops/ms
ClientPb.listUser                        thrpt       3   5.223 ± 1.765  ops/ms
ClientPb.createUser                       avgt       3   4.814 ± 1.815   ms/op
ClientPb.existUser                        avgt       3   4.662 ± 1.934   ms/op
ClientPb.getUser                          avgt       3   4.884 ± 0.144   ms/op
ClientPb.listUser                         avgt       3   5.888 ± 4.805   ms/op
ClientPb.createUser                     sample  196473   4.881 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.034           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.824           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  202113   4.748 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.912           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.262           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.531           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.584           ms/op
ClientPb.getUser                        sample  189984   5.051 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.709           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.256           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.823           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.098           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  166308   5.770 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.255           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.391           ms/op
