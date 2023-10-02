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
# Warmup Iteration   1: 1.517 ops/ms
# Warmup Iteration   2: 3.192 ops/ms
# Warmup Iteration   3: 7.045 ops/ms
Iteration   1: 7.760 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.029 ±(99.9%) 5.632 ops/ms [Average]
  (min, avg, max) = (7.760, 8.029, 8.366), stdev = 0.309
  CI (99.9%): [2.397, 13.661] (assumes normal distribution)


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
# Warmup Iteration   1: 2.255 ops/ms
# Warmup Iteration   2: 6.561 ops/ms
# Warmup Iteration   3: 7.811 ops/ms
Iteration   1: 8.214 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.304 ±(99.9%) 2.707 ops/ms [Average]
  (min, avg, max) = (8.214, 8.304, 8.475), stdev = 0.148
  CI (99.9%): [5.597, 11.011] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 6.234 ops/ms
# Warmup Iteration   3: 7.512 ops/ms
Iteration   1: 7.654 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 7.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.883 ±(99.9%) 4.266 ops/ms [Average]
  (min, avg, max) = (7.654, 7.883, 8.121), stdev = 0.234
  CI (99.9%): [3.617, 12.149] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.042 ops/ms
# Warmup Iteration   2: 5.714 ops/ms
# Warmup Iteration   3: 6.501 ops/ms
Iteration   1: 6.507 ops/ms
Iteration   2: 6.630 ops/ms
Iteration   3: 6.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.613 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (6.507, 6.613, 6.703), stdev = 0.099
  CI (99.9%): [4.804, 8.422] (assumes normal distribution)


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
# Warmup Iteration   1: 13.790 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.010 ms/op
Iteration   1: 4.374 ±(99.9%) 0.004 ms/op
Iteration   2: 3.971 ±(99.9%) 0.007 ms/op
Iteration   3: 4.196 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.180 ±(99.9%) 3.679 ms/op [Average]
  (min, avg, max) = (3.971, 4.180, 4.374), stdev = 0.202
  CI (99.9%): [0.502, 7.859] (assumes normal distribution)


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
# Warmup Iteration   1: 12.978 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.008 ms/op
Iteration   1: 4.083 ±(99.9%) 0.007 ms/op
Iteration   2: 4.046 ±(99.9%) 0.005 ms/op
Iteration   3: 3.831 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.986 ±(99.9%) 2.479 ms/op [Average]
  (min, avg, max) = (3.831, 3.986, 4.083), stdev = 0.136
  CI (99.9%): [1.507, 6.466] (assumes normal distribution)


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
# Warmup Iteration   1: 13.045 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.006 ms/op
Iteration   1: 4.235 ±(99.9%) 0.006 ms/op
Iteration   2: 4.104 ±(99.9%) 0.011 ms/op
Iteration   3: 4.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.160 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (4.104, 4.160, 4.235), stdev = 0.068
  CI (99.9%): [2.921, 5.399] (assumes normal distribution)


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
# Warmup Iteration   1: 14.015 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.426 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.010 ms/op
Iteration   1: 5.039 ±(99.9%) 0.006 ms/op
Iteration   2: 4.787 ±(99.9%) 0.007 ms/op
Iteration   3: 4.827 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.884 ±(99.9%) 2.478 ms/op [Average]
  (min, avg, max) = (4.787, 4.884, 5.039), stdev = 0.136
  CI (99.9%): [2.407, 7.362] (assumes normal distribution)


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
# Warmup Iteration   1: 14.270 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.018 ms/op
Iteration   1: 4.149 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 22.488 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 4.209 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  20.646 ms/op
                 createUser·p0.9999: 23.037 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 4.185 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  20.432 ms/op
                 createUser·p0.9999: 28.433 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229466
  mean =      4.181 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 475 
    [ 2.500,  5.000) = 208711 
    [ 5.000,  7.500) = 17055 
    [ 7.500, 10.000) = 2260 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     28.685 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 12.394 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 25.094 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.938 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   8.086 ms/op
                 existUser·p0.999:  24.566 ms/op
                 existUser·p0.9999: 27.357 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.852 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 29.285 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246277
  mean =      3.897 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 236101 
    [ 5.000,  7.500) = 7427 
    [ 7.500, 10.000) = 1682 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     28.193 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 12.716 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.017 ms/op
Iteration   1: 4.108 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  23.560 ms/op
                 getUser·p0.9999: 29.079 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 4.020 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 27.397 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.986 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.946 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.719 ms/op
                 getUser·p0.999:  27.263 ms/op
                 getUser·p0.9999: 30.670 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237759
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 227094 
    [ 5.000,  7.500) = 8025 
    [ 7.500, 10.000) = 1635 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.614 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     30.056 ms/op
     p(99.9990) =     31.347 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 15.975 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.597 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.876 ±(99.9%) 0.016 ms/op
Iteration   1: 4.757 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.440 ms/op
                 listUser·p0.999:  22.296 ms/op
                 listUser·p0.9999: 27.829 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 4.819 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 29.393 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   3: 4.761 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  16.480 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200750
  mean =      4.779 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 162802 
    [ 5.000,  7.500) = 33680 
    [ 7.500, 10.000) = 3254 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.029 ± 5.632  ops/ms
ClientPb.existUser                       thrpt       3   8.304 ± 2.707  ops/ms
ClientPb.getUser                         thrpt       3   7.883 ± 4.266  ops/ms
ClientPb.listUser                        thrpt       3   6.613 ± 1.809  ops/ms
ClientPb.createUser                       avgt       3   4.180 ± 3.679   ms/op
ClientPb.existUser                        avgt       3   3.986 ± 2.479   ms/op
ClientPb.getUser                          avgt       3   4.160 ± 1.239   ms/op
ClientPb.listUser                         avgt       3   4.884 ± 2.478   ms/op
ClientPb.createUser                     sample  229466   4.181 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.595           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.120           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.689           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  246277   3.897 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.511           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  237759   4.038 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.614           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.056           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  200750   4.779 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.135           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.295           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
