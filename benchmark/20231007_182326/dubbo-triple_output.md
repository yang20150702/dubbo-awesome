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
# Warmup Iteration   1: 1.220 ops/ms
# Warmup Iteration   2: 3.000 ops/ms
# Warmup Iteration   3: 5.156 ops/ms
Iteration   1: 5.467 ops/ms
Iteration   2: 5.813 ops/ms
Iteration   3: 6.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.775 ±(99.9%) 5.316 ops/ms [Average]
  (min, avg, max) = (5.467, 5.775, 6.046), stdev = 0.291
  CI (99.9%): [0.459, 11.091] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.605 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 6.322 ops/ms
Iteration   1: 6.194 ops/ms
Iteration   2: 6.487 ops/ms
Iteration   3: 6.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.320 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (6.194, 6.320, 6.487), stdev = 0.151
  CI (99.9%): [3.574, 9.067] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.945 ops/ms
# Warmup Iteration   2: 5.454 ops/ms
# Warmup Iteration   3: 5.930 ops/ms
Iteration   1: 6.157 ops/ms
Iteration   2: 6.020 ops/ms
Iteration   3: 6.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.092 ±(99.9%) 1.260 ops/ms [Average]
  (min, avg, max) = (6.020, 6.092, 6.157), stdev = 0.069
  CI (99.9%): [4.831, 7.352] (assumes normal distribution)


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
# Warmup Iteration   1: 1.607 ops/ms
# Warmup Iteration   2: 4.109 ops/ms
# Warmup Iteration   3: 5.084 ops/ms
Iteration   1: 5.213 ops/ms
Iteration   2: 4.860 ops/ms
Iteration   3: 5.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.107 ±(99.9%) 3.902 ops/ms [Average]
  (min, avg, max) = (4.860, 5.107, 5.246), stdev = 0.214
  CI (99.9%): [1.204, 9.009] (assumes normal distribution)


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
# Warmup Iteration   1: 16.593 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.007 ms/op
Iteration   1: 5.341 ±(99.9%) 0.007 ms/op
Iteration   2: 5.540 ±(99.9%) 0.009 ms/op
Iteration   3: 5.407 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.429 ±(99.9%) 1.855 ms/op [Average]
  (min, avg, max) = (5.341, 5.429, 5.540), stdev = 0.102
  CI (99.9%): [3.574, 7.284] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.737 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.388 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.186 ±(99.9%) 0.006 ms/op
Iteration   1: 5.139 ±(99.9%) 0.008 ms/op
Iteration   2: 5.120 ±(99.9%) 0.008 ms/op
Iteration   3: 5.241 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.167 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (5.120, 5.167, 5.241), stdev = 0.065
  CI (99.9%): [3.977, 6.356] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.967 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.008 ms/op
Iteration   1: 5.476 ±(99.9%) 0.011 ms/op
Iteration   2: 5.351 ±(99.9%) 0.008 ms/op
Iteration   3: 5.204 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.344 ±(99.9%) 2.491 ms/op [Average]
  (min, avg, max) = (5.204, 5.344, 5.476), stdev = 0.137
  CI (99.9%): [2.853, 7.834] (assumes normal distribution)


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
# Warmup Iteration   1: 17.565 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.320 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.402 ±(99.9%) 0.010 ms/op
Iteration   1: 6.217 ±(99.9%) 0.011 ms/op
Iteration   2: 6.685 ±(99.9%) 0.009 ms/op
Iteration   3: 6.361 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.421 ±(99.9%) 4.371 ms/op [Average]
  (min, avg, max) = (6.217, 6.421, 6.685), stdev = 0.240
  CI (99.9%): [2.050, 10.792] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.398 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.386 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.025 ms/op
Iteration   1: 5.454 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  22.029 ms/op
                 createUser·p0.9999: 26.877 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 5.472 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  25.514 ms/op
                 createUser·p0.9999: 28.448 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 5.364 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.048 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.078 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  26.523 ms/op
                 createUser·p0.9999: 33.330 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176620
  mean =      5.429 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 69966 
    [ 5.000,  7.500) = 98686 
    [ 7.500, 10.000) = 6067 
    [10.000, 12.500) = 1284 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 15.285 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.450 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.254 ±(99.9%) 0.018 ms/op
Iteration   1: 5.140 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.365 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 26.119 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 5.240 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   10.091 ms/op
                 existUser·p0.999:  28.605 ms/op
                 existUser·p0.9999: 33.505 ms/op
                 existUser·p1.00:   35.389 ms/op

Iteration   3: 5.253 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.095 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.647 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  26.750 ms/op
                 existUser·p0.9999: 32.468 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184076
  mean =      5.211 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 100352 
    [ 5.000,  7.500) = 74716 
    [ 7.500, 10.000) = 7133 
    [10.000, 12.500) = 1173 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     17.823 ms/op
     p(99.9900) =     32.558 ms/op
     p(99.9990) =     35.224 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 16.288 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.333 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.552 ±(99.9%) 0.021 ms/op
Iteration   1: 5.406 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   7.430 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 30.968 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   2: 5.496 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.888 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  22.621 ms/op
                 getUser·p0.9999: 29.148 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 5.407 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.597 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.332 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  16.450 ms/op
                 getUser·p0.9999: 28.850 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176597
  mean =      5.436 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 70818 
    [ 5.000,  7.500) = 97074 
    [ 7.500, 10.000) = 6739 
    [10.000, 12.500) = 1195 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.597 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     19.084 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     31.168 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 17.355 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.607 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.561 ±(99.9%) 0.023 ms/op
Iteration   1: 6.490 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.500 ms/op
                 listUser·p0.999:  27.689 ms/op
                 listUser·p0.9999: 29.852 ms/op
                 listUser·p1.00:   30.343 ms/op

Iteration   2: 6.256 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.873 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  29.143 ms/op
                 listUser·p0.9999: 32.393 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   3: 6.299 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.871 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  23.225 ms/op
                 listUser·p0.9999: 32.431 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151156
  mean =      6.347 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 9758 
    [ 5.000,  7.500) = 123361 
    [ 7.500, 10.000) = 14212 
    [10.000, 12.500) = 2610 
    [12.500, 15.000) = 603 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.331 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     27.192 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     33.666 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.775 ± 5.316  ops/ms
ClientPb.existUser                       thrpt       3   6.320 ± 2.747  ops/ms
ClientPb.getUser                         thrpt       3   6.092 ± 1.260  ops/ms
ClientPb.listUser                        thrpt       3   5.107 ± 3.902  ops/ms
ClientPb.createUser                       avgt       3   5.429 ± 1.855   ms/op
ClientPb.existUser                        avgt       3   5.167 ± 1.189   ms/op
ClientPb.getUser                          avgt       3   5.344 ± 2.491   ms/op
ClientPb.listUser                         avgt       3   6.421 ± 4.371   ms/op
ClientPb.createUser                     sample  176620   5.429 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.823           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.109           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  184076   5.211 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.095           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.455           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.823           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.558           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  176597   5.436 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.273           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.084           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  151156   6.347 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.192           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.014           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
