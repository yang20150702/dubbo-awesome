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
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 4.143 ops/ms
# Warmup Iteration   3: 7.560 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.751 ±(99.9%) 4.856 ops/ms [Average]
  (min, avg, max) = (7.457, 7.751, 7.974), stdev = 0.266
  CI (99.9%): [2.896, 12.607] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.209 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.236 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.366 ±(99.9%) 2.515 ops/ms [Average]
  (min, avg, max) = (8.236, 8.366, 8.511), stdev = 0.138
  CI (99.9%): [5.851, 10.881] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.824 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.920 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.938 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (7.881, 7.938, 8.012), stdev = 0.067
  CI (99.9%): [6.715, 9.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.946 ops/ms
# Warmup Iteration   2: 5.122 ops/ms
# Warmup Iteration   3: 6.579 ops/ms
Iteration   1: 6.633 ops/ms
Iteration   2: 6.753 ops/ms
Iteration   3: 6.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.708 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (6.633, 6.708, 6.753), stdev = 0.065
  CI (99.9%): [5.524, 7.892] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.690 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.005 ms/op
Iteration   1: 3.966 ±(99.9%) 0.005 ms/op
Iteration   2: 3.936 ±(99.9%) 0.008 ms/op
Iteration   3: 3.970 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.958 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.936, 3.958, 3.970), stdev = 0.019
  CI (99.9%): [3.620, 4.295] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.028 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.005 ms/op
Iteration   1: 3.820 ±(99.9%) 0.004 ms/op
Iteration   2: 3.861 ±(99.9%) 0.003 ms/op
Iteration   3: 3.835 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.839 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.820, 3.839, 3.861), stdev = 0.020
  CI (99.9%): [3.466, 4.211] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.757 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.004 ms/op
Iteration   1: 4.087 ±(99.9%) 0.004 ms/op
Iteration   2: 3.966 ±(99.9%) 0.004 ms/op
Iteration   3: 4.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.019 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (3.966, 4.019, 4.087), stdev = 0.062
  CI (99.9%): [2.889, 5.150] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.802 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.434 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.008 ms/op
Iteration   1: 4.703 ±(99.9%) 0.008 ms/op
Iteration   2: 4.636 ±(99.9%) 0.011 ms/op
Iteration   3: 4.739 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.693 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (4.636, 4.693, 4.739), stdev = 0.052
  CI (99.9%): [3.739, 5.646] (assumes normal distribution)


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
# Warmup Iteration   1: 12.956 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.938 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.018 ms/op
Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  13.550 ms/op
                 createUser·p0.9999: 20.614 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.575 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  12.975 ms/op
                 createUser·p0.9999: 24.837 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238649
  mean =      4.022 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 381 
    [ 2.500,  5.000) = 226151 
    [ 5.000,  7.500) = 10028 
    [ 7.500, 10.000) = 1599 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     13.790 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     25.470 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 10.633 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  23.298 ms/op
                 existUser·p0.9999: 25.523 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.105 ms/op
                 existUser·p0.999:  13.451 ms/op
                 existUser·p0.9999: 27.387 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.965 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.944 ms/op
                 existUser·p0.999:  15.742 ms/op
                 existUser·p0.9999: 29.489 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242302
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 312 
    [ 2.500,  5.000) = 232098 
    [ 5.000,  7.500) = 7879 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.347 ms/op
     p(99.9900) =     28.370 ms/op
     p(99.9990) =     29.934 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 13.392 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.015 ms/op
Iteration   1: 4.110 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  24.445 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  14.664 ms/op
                 getUser·p0.9999: 27.260 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  27.066 ms/op
                 getUser·p0.9999: 28.697 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239401
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 228862 
    [ 5.000,  7.500) = 7555 
    [ 7.500, 10.000) = 2150 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 162 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     24.359 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.511 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 14.296 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.363 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.017 ms/op
Iteration   1: 4.642 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  25.166 ms/op
                 listUser·p0.9999: 29.182 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   2: 4.794 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.636 ms/op
                 listUser·p0.9999: 24.336 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.696 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  16.447 ms/op
                 listUser·p0.9999: 18.723 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203736
  mean =      4.710 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 169591 
    [ 5.000,  7.500) = 30720 
    [ 7.500, 10.000) = 2564 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     18.474 ms/op
     p(99.9900) =     27.251 ms/op
     p(99.9990) =     29.748 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.751 ± 4.856  ops/ms
ClientPb.existUser                       thrpt       3   8.366 ± 2.515  ops/ms
ClientPb.getUser                         thrpt       3   7.938 ± 1.223  ops/ms
ClientPb.listUser                        thrpt       3   6.708 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   3.958 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   3.839 ± 0.372   ms/op
ClientPb.getUser                          avgt       3   4.019 ± 1.130   ms/op
ClientPb.listUser                         avgt       3   4.693 ± 0.953   ms/op
ClientPb.createUser                     sample  238649   4.022 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.790           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.314           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  242302   3.962 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.906           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.347           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.370           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  239401   4.005 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.249           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.359           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  203736   4.710 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.888           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.474           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.251           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.015           ms/op
