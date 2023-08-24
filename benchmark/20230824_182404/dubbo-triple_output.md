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
# Warmup Iteration   1: 1.707 ops/ms
# Warmup Iteration   2: 3.481 ops/ms
# Warmup Iteration   3: 6.765 ops/ms
Iteration   1: 7.149 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.555 ±(99.9%) 6.824 ops/ms [Average]
  (min, avg, max) = (7.149, 7.555, 7.886), stdev = 0.374
  CI (99.9%): [0.731, 14.379] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 8.370 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.138 ±(99.9%) 5.318 ops/ms [Average]
  (min, avg, max) = (7.811, 8.138, 8.370), stdev = 0.292
  CI (99.9%): [2.820, 13.457] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 6.907 ops/ms
# Warmup Iteration   3: 7.099 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 7.692 ops/ms
Iteration   3: 8.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.832 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (7.692, 7.832, 8.004), stdev = 0.159
  CI (99.9%): [4.934, 10.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.577 ops/ms
# Warmup Iteration   3: 6.420 ops/ms
Iteration   1: 6.751 ops/ms
Iteration   2: 6.936 ops/ms
Iteration   3: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.834 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (6.751, 6.834, 6.936), stdev = 0.094
  CI (99.9%): [5.121, 8.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.756 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.005 ms/op
Iteration   1: 3.951 ±(99.9%) 0.009 ms/op
Iteration   2: 3.940 ±(99.9%) 0.008 ms/op
Iteration   3: 3.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.951 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.940, 3.951, 3.964), stdev = 0.012
  CI (99.9%): [3.733, 4.170] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.682 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.005 ms/op
Iteration   1: 3.864 ±(99.9%) 0.006 ms/op
Iteration   2: 3.804 ±(99.9%) 0.004 ms/op
Iteration   3: 3.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.861 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.804, 3.861, 3.917), stdev = 0.056
  CI (99.9%): [2.837, 4.886] (assumes normal distribution)


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
# Warmup Iteration   1: 11.743 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.792 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.004 ms/op
Iteration   1: 4.072 ±(99.9%) 0.007 ms/op
Iteration   2: 4.094 ±(99.9%) 0.006 ms/op
Iteration   3: 4.025 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.063 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (4.025, 4.063, 4.094), stdev = 0.035
  CI (99.9%): [3.425, 4.702] (assumes normal distribution)


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
# Warmup Iteration   1: 14.121 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.009 ms/op
Iteration   1: 4.764 ±(99.9%) 0.015 ms/op
Iteration   2: 4.813 ±(99.9%) 0.009 ms/op
Iteration   3: 4.950 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.842 ±(99.9%) 1.761 ms/op [Average]
  (min, avg, max) = (4.764, 4.842, 4.950), stdev = 0.097
  CI (99.9%): [3.081, 6.604] (assumes normal distribution)


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
# Warmup Iteration   1: 12.698 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 5.207 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.645 ±(99.9%) 0.021 ms/op
Iteration   1: 3.872 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 42.992 ms/op
                 createUser·p1.00:   44.106 ms/op

Iteration   2: 3.906 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.294 ms/op
                 createUser·p0.999:  25.044 ms/op
                 createUser·p0.9999: 28.180 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 4.131 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 31.433 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241874
  mean =      3.966 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229079 
    [ 5.000, 10.000) = 11711 
    [10.000, 15.000) = 746 
    [15.000, 20.000) = 56 
    [20.000, 25.000) = 69 
    [25.000, 30.000) = 153 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     41.746 ms/op
     p(99.9990) =     43.837 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.264 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
Iteration   1: 4.215 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   8.765 ms/op
                 existUser·p0.999:  13.907 ms/op
                 existUser·p0.9999: 25.540 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.988 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.710 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.854 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 30.868 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239054
  mean =      4.013 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 224229 
    [ 5.000,  7.500) = 10611 
    [ 7.500, 10.000) = 2770 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     31.499 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 13.270 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.014 ms/op
Iteration   1: 4.137 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   9.503 ms/op
                 getUser·p0.999:  23.518 ms/op
                 getUser·p0.9999: 35.062 ms/op
                 getUser·p1.00:   39.191 ms/op

Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 29.565 ms/op
                 getUser·p1.00:   31.523 ms/op

Iteration   3: 4.042 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  26.695 ms/op
                 getUser·p0.9999: 31.706 ms/op
                 getUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235217
  mean =      4.079 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 221020 
    [ 5.000,  7.500) = 10468 
    [ 7.500, 10.000) = 2472 
    [10.000, 12.500) = 803 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     23.761 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     35.880 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 14.042 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.228 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.017 ms/op
Iteration   1: 4.765 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  22.249 ms/op
                 listUser·p0.9999: 27.778 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   2: 4.597 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.708 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 18.633 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204622
  mean =      4.689 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 173787 
    [ 5.000,  7.500) = 24161 
    [ 7.500, 10.000) = 5121 
    [10.000, 12.500) = 893 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.990 ms/op
     p(99.9990) =     28.370 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.555 ± 6.824  ops/ms
ClientPb.existUser                       thrpt       3   8.138 ± 5.318  ops/ms
ClientPb.getUser                         thrpt       3   7.832 ± 2.898  ops/ms
ClientPb.listUser                        thrpt       3   6.834 ± 1.714  ops/ms
ClientPb.createUser                       avgt       3   3.951 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   3.861 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   4.063 ± 0.638   ms/op
ClientPb.listUser                         avgt       3   4.842 ± 1.761   ms/op
ClientPb.createUser                     sample  241874   3.966 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.746           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.106           ms/op
ClientPb.existUser                      sample  239054   4.013 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.331           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.483           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.065           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.408           ms/op
ClientPb.getUser                        sample  235217   4.079 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.382           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.364           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.761           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.191           ms/op
ClientPb.listUser                       sample  204622   4.689 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.044           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.990           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.032           ms/op
