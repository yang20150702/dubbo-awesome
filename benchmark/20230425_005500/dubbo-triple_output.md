# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.940 ops/ms
# Warmup Iteration   2: 2.133 ops/ms
# Warmup Iteration   3: 5.065 ops/ms
Iteration   1: 5.520 ops/ms
Iteration   2: 6.295 ops/ms
Iteration   3: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.992 ±(99.9%) 7.553 ops/ms [Average]
  (min, avg, max) = (5.520, 5.992, 6.295), stdev = 0.414
  CI (99.9%): [≈ 0, 13.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 5.133 ops/ms
# Warmup Iteration   3: 6.149 ops/ms
Iteration   1: 6.361 ops/ms
Iteration   2: 6.804 ops/ms
Iteration   3: 6.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.544 ±(99.9%) 4.218 ops/ms [Average]
  (min, avg, max) = (6.361, 6.544, 6.804), stdev = 0.231
  CI (99.9%): [2.325, 10.762] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.715 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 6.055 ops/ms
Iteration   1: 5.619 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.665 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (5.594, 5.665, 5.783), stdev = 0.103
  CI (99.9%): [3.793, 7.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.306 ops/ms
# Warmup Iteration   2: 3.888 ops/ms
# Warmup Iteration   3: 4.784 ops/ms
Iteration   1: 5.207 ops/ms
Iteration   2: 5.052 ops/ms
Iteration   3: 5.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.110 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (5.052, 5.110, 5.207), stdev = 0.084
  CI (99.9%): [3.573, 6.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 21.616 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 7.178 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.800 ±(99.9%) 0.014 ms/op
Iteration   1: 5.635 ±(99.9%) 0.013 ms/op
Iteration   2: 5.409 ±(99.9%) 0.020 ms/op
Iteration   3: 5.369 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.471 ±(99.9%) 2.611 ms/op [Average]
  (min, avg, max) = (5.369, 5.471, 5.635), stdev = 0.143
  CI (99.9%): [2.860, 8.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 20.614 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.383 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.291 ±(99.9%) 0.011 ms/op
Iteration   1: 5.492 ±(99.9%) 0.006 ms/op
Iteration   2: 5.394 ±(99.9%) 0.009 ms/op
Iteration   3: 5.235 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.374 ±(99.9%) 2.363 ms/op [Average]
  (min, avg, max) = (5.235, 5.374, 5.492), stdev = 0.130
  CI (99.9%): [3.011, 7.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 17.929 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 7.472 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.575 ±(99.9%) 0.017 ms/op
Iteration   1: 5.431 ±(99.9%) 0.016 ms/op
Iteration   2: 5.584 ±(99.9%) 0.010 ms/op
Iteration   3: 5.556 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.524 ±(99.9%) 1.491 ms/op [Average]
  (min, avg, max) = (5.431, 5.524, 5.584), stdev = 0.082
  CI (99.9%): [4.033, 7.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.264 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 8.480 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.748 ±(99.9%) 0.015 ms/op
Iteration   1: 6.580 ±(99.9%) 0.013 ms/op
Iteration   2: 6.139 ±(99.9%) 0.017 ms/op
Iteration   3: 5.968 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.229 ±(99.9%) 5.759 ms/op [Average]
  (min, avg, max) = (5.968, 6.229, 6.580), stdev = 0.316
  CI (99.9%): [0.470, 11.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 18.787 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.023 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.032 ms/op
Iteration   1: 5.653 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.078 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   12.386 ms/op
                 createUser·p0.999:  23.884 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 5.563 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.848 ms/op
                 createUser·p0.999:  26.313 ms/op
                 createUser·p0.9999: 30.606 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   3: 5.552 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   8.323 ms/op
                 createUser·p0.99:   11.862 ms/op
                 createUser·p0.999:  25.854 ms/op
                 createUser·p0.9999: 34.800 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171754
  mean =      5.589 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 70016 
    [ 5.000,  7.500) = 88828 
    [ 7.500, 10.000) = 8845 
    [10.000, 12.500) = 2597 
    [12.500, 15.000) = 875 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.951 ms/op
     p(99.9000) =     24.527 ms/op
     p(99.9900) =     33.607 ms/op
     p(99.9990) =     35.032 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 19.730 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.342 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.024 ms/op
Iteration   1: 5.196 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.922 ms/op
                 existUser·p0.99:   10.240 ms/op
                 existUser·p0.999:  16.707 ms/op
                 existUser·p0.9999: 27.230 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 5.022 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  24.353 ms/op
                 existUser·p0.9999: 34.079 ms/op
                 existUser·p1.00:   35.455 ms/op

Iteration   3: 5.035 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   7.408 ms/op
                 existUser·p0.99:   11.174 ms/op
                 existUser·p0.999:  25.943 ms/op
                 existUser·p0.9999: 29.239 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188853
  mean =      5.083 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 122646 
    [ 5.000,  7.500) = 56178 
    [ 7.500, 10.000) = 7568 
    [10.000, 12.500) = 1667 
    [12.500, 15.000) = 456 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     19.076 ms/op
     p(99.9900) =     33.249 ms/op
     p(99.9990) =     34.465 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 16.598 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 6.442 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.309 ±(99.9%) 0.020 ms/op
Iteration   1: 5.322 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   10.994 ms/op
                 getUser·p0.999:  22.194 ms/op
                 getUser·p0.9999: 24.835 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 5.293 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.499 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   11.334 ms/op
                 getUser·p0.999:  22.217 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 5.338 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.001 ms/op
                 getUser·p0.90:   6.554 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.715 ms/op
                 getUser·p0.999:  25.809 ms/op
                 getUser·p0.9999: 30.016 ms/op
                 getUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180612
  mean =      5.318 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 94140 
    [ 5.000,  7.500) = 75469 
    [ 7.500, 10.000) = 8096 
    [10.000, 12.500) = 1907 
    [12.500, 15.000) = 636 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     22.282 ms/op
     p(99.9900) =     29.028 ms/op
     p(99.9990) =     30.795 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.674 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.810 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.078 ±(99.9%) 0.025 ms/op
Iteration   1: 5.882 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.933 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  26.473 ms/op
                 listUser·p0.9999: 37.917 ms/op
                 listUser·p1.00:   41.353 ms/op

Iteration   2: 6.374 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  28.985 ms/op
                 listUser·p0.9999: 31.649 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   3: 6.583 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   8.184 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  24.276 ms/op
                 listUser·p0.9999: 27.726 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153065
  mean =      6.266 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13896 
    [ 5.000, 10.000) = 134302 
    [10.000, 15.000) = 4112 
    [15.000, 20.000) = 342 
    [20.000, 25.000) = 175 
    [25.000, 30.000) = 188 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.812 ms/op
     p(99.9000) =     27.066 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     39.893 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.992 ± 7.553  ops/ms
ClientPb.existUser                       thrpt       3   6.544 ± 4.218  ops/ms
ClientPb.getUser                         thrpt       3   5.665 ± 1.872  ops/ms
ClientPb.listUser                        thrpt       3   5.110 ± 1.537  ops/ms
ClientPb.createUser                       avgt       3   5.471 ± 2.611   ms/op
ClientPb.existUser                        avgt       3   5.374 ± 2.363   ms/op
ClientPb.getUser                          avgt       3   5.524 ± 1.491   ms/op
ClientPb.listUser                         avgt       3   6.229 ± 5.759   ms/op
ClientPb.createUser                     sample  171754   5.589 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.739           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.389           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.951           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.527           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.607           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  188853   5.083 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.807           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.594           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.633           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.076           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.249           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.455           ms/op
ClientPb.getUser                        sample  180612   5.318 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.397           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.010           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  153065   6.266 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.432           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.812           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.066           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.356           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.353           ms/op
