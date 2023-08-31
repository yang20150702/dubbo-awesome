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
# Warmup Iteration   1: 1.359 ops/ms
# Warmup Iteration   2: 3.097 ops/ms
# Warmup Iteration   3: 6.232 ops/ms
Iteration   1: 7.069 ops/ms
Iteration   2: 7.332 ops/ms
Iteration   3: 7.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.289 ±(99.9%) 3.693 ops/ms [Average]
  (min, avg, max) = (7.069, 7.289, 7.467), stdev = 0.202
  CI (99.9%): [3.596, 10.982] (assumes normal distribution)


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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 6.375 ops/ms
# Warmup Iteration   3: 7.571 ops/ms
Iteration   1: 7.802 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.894 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (7.802, 7.894, 8.009), stdev = 0.105
  CI (99.9%): [5.972, 9.817] (assumes normal distribution)


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
# Warmup Iteration   1: 1.954 ops/ms
# Warmup Iteration   2: 5.717 ops/ms
# Warmup Iteration   3: 7.217 ops/ms
Iteration   1: 7.419 ops/ms
Iteration   2: 7.614 ops/ms
Iteration   3: 7.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.526 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (7.419, 7.526, 7.614), stdev = 0.099
  CI (99.9%): [5.729, 9.323] (assumes normal distribution)


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
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 6.122 ops/ms
Iteration   1: 6.262 ops/ms
Iteration   2: 6.427 ops/ms
Iteration   3: 6.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.384 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (6.262, 6.384, 6.463), stdev = 0.107
  CI (99.9%): [4.433, 8.335] (assumes normal distribution)


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
# Warmup Iteration   1: 15.286 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.251 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.007 ms/op
Iteration   1: 4.214 ±(99.9%) 0.006 ms/op
Iteration   2: 4.108 ±(99.9%) 0.009 ms/op
Iteration   3: 4.142 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.154 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (4.108, 4.154, 4.214), stdev = 0.054
  CI (99.9%): [3.167, 5.142] (assumes normal distribution)


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
# Warmup Iteration   1: 11.957 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.004 ms/op
Iteration   1: 4.059 ±(99.9%) 0.005 ms/op
Iteration   2: 4.122 ±(99.9%) 0.005 ms/op
Iteration   3: 4.155 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.112 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (4.059, 4.112, 4.155), stdev = 0.049
  CI (99.9%): [3.227, 4.998] (assumes normal distribution)


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
# Warmup Iteration   1: 13.752 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.008 ms/op
Iteration   1: 4.377 ±(99.9%) 0.004 ms/op
Iteration   2: 4.269 ±(99.9%) 0.007 ms/op
Iteration   3: 4.163 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.270 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (4.163, 4.270, 4.377), stdev = 0.107
  CI (99.9%): [2.319, 6.220] (assumes normal distribution)


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
# Warmup Iteration   1: 15.098 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.222 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.046 ±(99.9%) 0.013 ms/op
Iteration   1: 5.194 ±(99.9%) 0.010 ms/op
Iteration   2: 5.086 ±(99.9%) 0.010 ms/op
Iteration   3: 4.960 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.080 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (4.960, 5.080, 5.194), stdev = 0.117
  CI (99.9%): [2.948, 7.212] (assumes normal distribution)


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
# Warmup Iteration   1: 13.836 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.367 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.496 ±(99.9%) 0.018 ms/op
Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  22.325 ms/op
                 createUser·p0.9999: 24.743 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 4.361 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 30.419 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 4.260 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   4.096 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  26.636 ms/op
                 createUser·p0.9999: 28.721 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 224890
  mean =      4.268 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 205709 
    [ 5.000,  7.500) = 16010 
    [ 7.500, 10.000) = 1958 
    [10.000, 12.500) = 508 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     22.876 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     30.958 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 13.530 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.015 ms/op
Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.888 ms/op
                 existUser·p0.999:  12.997 ms/op
                 existUser·p0.9999: 30.682 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   2: 4.103 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 28.220 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 4.169 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   8.405 ms/op
                 existUser·p0.999:  15.733 ms/op
                 existUser·p0.9999: 31.752 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 233031
  mean =      4.119 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 272 
    [ 2.500,  5.000) = 213972 
    [ 5.000,  7.500) = 14136 
    [ 7.500, 10.000) = 3796 
    [10.000, 12.500) = 516 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     31.175 ms/op
     p(99.9990) =     32.004 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 13.530 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.017 ms/op
Iteration   1: 4.216 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 27.468 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 4.206 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  16.208 ms/op
                 getUser·p0.9999: 28.128 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 4.285 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  19.116 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226474
  mean =      4.236 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 209568 
    [ 5.000,  7.500) = 12813 
    [ 7.500, 10.000) = 2895 
    [10.000, 12.500) = 718 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 142 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     19.400 ms/op
     p(99.9900) =     28.924 ms/op
     p(99.9990) =     29.907 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 15.569 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.623 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.017 ms/op
Iteration   1: 4.952 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  23.410 ms/op
                 listUser·p0.9999: 25.955 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 5.127 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 26.953 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 5.179 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.680 ms/op
                 listUser·p0.999:  18.597 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 188707
  mean =      5.084 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 123061 
    [ 5.000,  7.500) = 57256 
    [ 7.500, 10.000) = 6428 
    [10.000, 12.500) = 1217 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     21.112 ms/op
     p(99.9900) =     25.998 ms/op
     p(99.9990) =     27.496 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.289 ± 3.693  ops/ms
ClientPb.existUser                       thrpt       3   7.894 ± 1.923  ops/ms
ClientPb.getUser                         thrpt       3   7.526 ± 1.797  ops/ms
ClientPb.listUser                        thrpt       3   6.384 ± 1.951  ops/ms
ClientPb.createUser                       avgt       3   4.154 ± 0.987   ms/op
ClientPb.existUser                        avgt       3   4.112 ± 0.885   ms/op
ClientPb.getUser                          avgt       3   4.270 ± 1.950   ms/op
ClientPb.listUser                         avgt       3   5.080 ± 2.132   ms/op
ClientPb.createUser                     sample  224890   4.268 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.579           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.876           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  233031   4.119 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.135           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.745           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.175           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  226474   4.236 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.503           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.924           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950           ms/op
ClientPb.listUser                       sample  188707   5.084 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.093           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.112           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.998           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
