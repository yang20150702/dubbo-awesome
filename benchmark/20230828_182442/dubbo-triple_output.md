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
# Warmup Iteration   1: 1.045 ops/ms
# Warmup Iteration   2: 1.551 ops/ms
# Warmup Iteration   3: 2.261 ops/ms
Iteration   1: 2.530 ops/ms
Iteration   2: 2.439 ops/ms
Iteration   3: 2.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.468 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (2.435, 2.468, 2.530), stdev = 0.054
  CI (99.9%): [1.483, 3.453] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 0.847 ops/ms
# Warmup Iteration   2: 1.894 ops/ms
# Warmup Iteration   3: 2.414 ops/ms
Iteration   1: 3.019 ops/ms
Iteration   2: 3.178 ops/ms
Iteration   3: 7.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.507 ±(99.9%) 44.533 ops/ms [Average]
  (min, avg, max) = (3.019, 4.507, 7.324), stdev = 2.441
  CI (99.9%): [≈ 0, 49.040] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 3.656 ops/ms
# Warmup Iteration   3: 6.639 ops/ms
Iteration   1: 7.210 ops/ms
Iteration   2: 6.689 ops/ms
Iteration   3: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.982 ±(99.9%) 4.861 ops/ms [Average]
  (min, avg, max) = (6.689, 6.982, 7.210), stdev = 0.266
  CI (99.9%): [2.121, 11.843] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.879 ops/ms
# Warmup Iteration   2: 4.370 ops/ms
# Warmup Iteration   3: 5.724 ops/ms
Iteration   1: 5.792 ops/ms
Iteration   2: 5.700 ops/ms
Iteration   3: 5.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.591 ±(99.9%) 4.976 ops/ms [Average]
  (min, avg, max) = (5.280, 5.591, 5.792), stdev = 0.273
  CI (99.9%): [0.614, 10.567] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 15.637 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.008 ms/op
Iteration   1: 4.930 ±(99.9%) 0.008 ms/op
Iteration   2: 4.925 ±(99.9%) 0.006 ms/op
Iteration   3: 4.534 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.796 ±(99.9%) 4.142 ms/op [Average]
  (min, avg, max) = (4.534, 4.796, 4.930), stdev = 0.227
  CI (99.9%): [0.655, 8.938] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.879 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.007 ms/op
Iteration   1: 4.595 ±(99.9%) 0.008 ms/op
Iteration   2: 4.453 ±(99.9%) 0.009 ms/op
Iteration   3: 4.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.533 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (4.453, 4.533, 4.595), stdev = 0.073
  CI (99.9%): [3.202, 5.865] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.439 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.007 ms/op
Iteration   1: 4.480 ±(99.9%) 0.007 ms/op
Iteration   2: 4.581 ±(99.9%) 0.006 ms/op
Iteration   3: 4.548 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.536 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (4.480, 4.536, 4.581), stdev = 0.051
  CI (99.9%): [3.597, 5.475] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 15.813 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.598 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.011 ms/op
Iteration   1: 5.609 ±(99.9%) 0.012 ms/op
Iteration   2: 5.698 ±(99.9%) 0.013 ms/op
Iteration   3: 5.686 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.664 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (5.609, 5.664, 5.698), stdev = 0.048
  CI (99.9%): [4.786, 6.543] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 14.909 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 6.282 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.024 ms/op
Iteration   1: 4.641 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  24.904 ms/op
                 createUser·p0.9999: 28.643 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   2: 4.538 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  16.671 ms/op
                 createUser·p0.9999: 32.296 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 4.585 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.960 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 209220
  mean =      4.588 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 160289 
    [ 5.000,  7.500) = 42294 
    [ 7.500, 10.000) = 4315 
    [10.000, 12.500) = 1363 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     24.634 ms/op
     p(99.9900) =     31.306 ms/op
     p(99.9990) =     33.054 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 13.692 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.277 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.019 ms/op
Iteration   1: 4.580 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  19.202 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   37.290 ms/op

Iteration   2: 4.384 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.717 ms/op
                 existUser·p0.999:  28.344 ms/op
                 existUser·p0.9999: 46.059 ms/op
                 existUser·p1.00:   46.531 ms/op

Iteration   3: 4.568 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  15.106 ms/op
                 existUser·p0.9999: 32.015 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 212771
  mean =      4.509 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 167116 
    [ 5.000, 10.000) = 43860 
    [10.000, 15.000) = 1476 
    [15.000, 20.000) = 94 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 97 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     24.598 ms/op
     p(99.9900) =     43.432 ms/op
     p(99.9990) =     46.391 ms/op
     p(99.9999) =     46.531 ms/op
    p(100.0000) =     46.531 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.256 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.399 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.018 ms/op
Iteration   1: 4.785 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.432 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 33.298 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   2: 4.697 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   7.029 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  16.036 ms/op
                 getUser·p0.9999: 32.190 ms/op
                 getUser·p1.00:   32.735 ms/op

Iteration   3: 4.712 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  14.370 ms/op
                 getUser·p0.9999: 33.961 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 202876
  mean =      4.731 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 146440 
    [ 5.000,  7.500) = 48191 
    [ 7.500, 10.000) = 6089 
    [10.000, 12.500) = 1372 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 74 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     33.667 ms/op
     p(99.9990) =     35.846 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 14.128 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 13.807 ±(99.9%) 0.153 ms/op
# Warmup Iteration   3: 14.823 ±(99.9%) 0.136 ms/op
Iteration   1: 13.238 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   3.617 ms/op
                 listUser·p0.50:   12.550 ms/op
                 listUser·p0.90:   19.104 ms/op
                 listUser·p0.95:   21.430 ms/op
                 listUser·p0.99:   27.853 ms/op
                 listUser·p0.999:  49.238 ms/op
                 listUser·p0.9999: 57.469 ms/op
                 listUser·p1.00:   58.130 ms/op

Iteration   2: 12.333 ±(99.9%) 0.087 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   11.682 ms/op
                 listUser·p0.90:   17.170 ms/op
                 listUser·p0.95:   19.137 ms/op
                 listUser·p0.99:   25.494 ms/op
                 listUser·p0.999:  46.992 ms/op
                 listUser·p0.9999: 51.290 ms/op
                 listUser·p1.00:   54.460 ms/op

Iteration   3: 11.196 ±(99.9%) 0.083 ms/op
                 listUser·p0.00:   3.297 ms/op
                 listUser·p0.50:   10.617 ms/op
                 listUser·p0.90:   16.024 ms/op
                 listUser·p0.95:   17.957 ms/op
                 listUser·p0.99:   21.627 ms/op
                 listUser·p0.999:  61.839 ms/op
                 listUser·p0.9999: 69.880 ms/op
                 listUser·p1.00:   71.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 78675
  mean =     12.198 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264 
    [ 5.000, 10.000) = 25450 
    [10.000, 15.000) = 37157 
    [15.000, 20.000) = 12473 
    [20.000, 25.000) = 2422 
    [25.000, 30.000) = 546 
    [30.000, 35.000) = 133 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 33 
    [45.000, 50.000) = 55 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 27 
    [60.000, 65.000) = 17 
    [65.000, 70.000) = 21 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.092 ms/op
     p(50.0000) =     11.534 ms/op
     p(90.0000) =     17.367 ms/op
     p(95.0000) =     19.595 ms/op
     p(99.0000) =     25.625 ms/op
     p(99.9000) =     51.051 ms/op
     p(99.9900) =     67.537 ms/op
     p(99.9990) =     71.303 ms/op
     p(99.9999) =     71.303 ms/op
    p(100.0000) =     71.303 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   2.468 ±  0.985  ops/ms
ClientPb.existUser                       thrpt       3   4.507 ± 44.533  ops/ms
ClientPb.getUser                         thrpt       3   6.982 ±  4.861  ops/ms
ClientPb.listUser                        thrpt       3   5.591 ±  4.976  ops/ms
ClientPb.createUser                       avgt       3   4.796 ±  4.142   ms/op
ClientPb.existUser                        avgt       3   4.533 ±  1.331   ms/op
ClientPb.getUser                          avgt       3   4.536 ±  0.939   ms/op
ClientPb.listUser                         avgt       3   5.664 ±  0.878   ms/op
ClientPb.createUser                     sample  209220   4.588 ±  0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.778            ms/op
ClientPb.createUser:createUser·p0.50    sample           4.190            ms/op
ClientPb.createUser:createUser·p0.90    sample           5.882            ms/op
ClientPb.createUser:createUser·p0.95    sample           6.758            ms/op
ClientPb.createUser:createUser·p0.99    sample           9.945            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.634            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.306            ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391            ms/op
ClientPb.existUser                      sample  212771   4.509 ±  0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.850            ms/op
ClientPb.existUser:existUser·p0.50      sample           4.100            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.808            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.767            ms/op
ClientPb.existUser:existUser·p0.99      sample           9.601            ms/op
ClientPb.existUser:existUser·p0.999     sample          24.598            ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.432            ms/op
ClientPb.existUser:existUser·p1.00      sample          46.531            ms/op
ClientPb.getUser                        sample  202876   4.731 ±  0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.432            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.334            ms/op
ClientPb.getUser:getUser·p0.90          sample           6.226            ms/op
ClientPb.getUser:getUser·p0.95          sample           7.168            ms/op
ClientPb.getUser:getUser·p0.99          sample          10.043            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.547            ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.667            ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045            ms/op
ClientPb.listUser                       sample   78675  12.198 ±  0.052   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.092            ms/op
ClientPb.listUser:listUser·p0.50        sample          11.534            ms/op
ClientPb.listUser:listUser·p0.90        sample          17.367            ms/op
ClientPb.listUser:listUser·p0.95        sample          19.595            ms/op
ClientPb.listUser:listUser·p0.99        sample          25.625            ms/op
ClientPb.listUser:listUser·p0.999       sample          51.051            ms/op
ClientPb.listUser:listUser·p0.9999      sample          67.537            ms/op
ClientPb.listUser:listUser·p1.00        sample          71.303            ms/op
