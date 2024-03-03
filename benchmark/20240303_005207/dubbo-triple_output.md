# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ops/ms
# Warmup Iteration   2: 12.335 ops/ms
# Warmup Iteration   3: 12.650 ops/ms
Iteration   1: 12.875 ops/ms
Iteration   2: 12.870 ops/ms
Iteration   3: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.860 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (12.834, 12.860, 12.875), stdev = 0.022
  CI (99.9%): [12.450, 13.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ops/ms
# Warmup Iteration   2: 13.417 ops/ms
# Warmup Iteration   3: 13.359 ops/ms
Iteration   1: 13.433 ops/ms
Iteration   2: 13.351 ops/ms
Iteration   3: 13.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.335 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (13.221, 13.335, 13.433), stdev = 0.107
  CI (99.9%): [11.386, 15.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.410 ops/ms
# Warmup Iteration   2: 12.801 ops/ms
# Warmup Iteration   3: 13.120 ops/ms
Iteration   1: 13.158 ops/ms
Iteration   2: 13.142 ops/ms
Iteration   3: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.194 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (13.142, 13.194, 13.281), stdev = 0.076
  CI (99.9%): [11.802, 14.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.722 ops/ms
# Warmup Iteration   2: 10.713 ops/ms
# Warmup Iteration   3: 10.812 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.721 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (10.658, 10.721, 10.764), stdev = 0.056
  CI (99.9%): [9.698, 11.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.003 ms/op
Iteration   2: 2.449 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.457 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.449, 2.457, 2.471), stdev = 0.012
  CI (99.9%): [2.234, 2.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.532 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.377 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.351 ±(99.9%) 0.004 ms/op
Iteration   1: 2.355 ±(99.9%) 0.004 ms/op
Iteration   2: 2.344 ±(99.9%) 0.004 ms/op
Iteration   3: 2.368 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.356 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.344, 2.356, 2.368), stdev = 0.012
  CI (99.9%): [2.136, 2.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.463, 2.470, 2.481), stdev = 0.010
  CI (99.9%): [2.288, 2.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.005 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
Iteration   2: 2.945 ±(99.9%) 0.004 ms/op
Iteration   3: 2.919 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.928 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.919, 2.928, 2.945), stdev = 0.015
  CI (99.9%): [2.659, 3.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  6.517 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.673 ms/op
                 createUser·p0.999:  9.897 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  8.391 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389103
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 191806 
    [ 2.500,  3.750) = 193210 
    [ 3.750,  5.000) = 3171 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.633 ms/op
     p(99.9900) =     12.800 ms/op
     p(99.9990) =     15.490 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.379 ±(99.9%) 0.005 ms/op
Iteration   1: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.797 ms/op
                 existUser·p0.9999: 13.701 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.732 ms/op
                 existUser·p0.999:  9.729 ms/op
                 existUser·p0.9999: 12.284 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.381 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.684 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401330
  mean =      2.390 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 206736 
    [ 2.500,  3.750) = 191316 
    [ 3.750,  5.000) = 2434 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      9.039 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.556 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.637 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390642
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 199503 
    [ 2.500,  3.750) = 185879 
    [ 3.750,  5.000) = 4216 
    [ 5.000,  6.250) = 547 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      6.882 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.962 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.542 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.586 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 13.208 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.412 ms/op
                 listUser·p0.9999: 10.572 ms/op
                 listUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320813
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 96436 
    [ 2.500,  3.750) = 186298 
    [ 3.750,  5.000) = 30978 
    [ 5.000,  6.250) = 5435 
    [ 6.250,  7.500) = 767 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 321 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.336 ms/op
     p(99.9990) =     14.113 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.860 ± 0.410  ops/ms
ClientPb.existUser                       thrpt       3  13.335 ± 1.949  ops/ms
ClientPb.getUser                         thrpt       3  13.194 ± 1.392  ops/ms
ClientPb.listUser                        thrpt       3  10.721 ± 1.024  ops/ms
ClientPb.createUser                       avgt       3   2.457 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   2.356 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.182   ms/op
ClientPb.listUser                         avgt       3   2.928 ± 0.269   ms/op
ClientPb.createUser                     sample  389103   2.465 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.633           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.800           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.614           ms/op
ClientPb.existUser                      sample  401330   2.390 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.481           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.039           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  390642   2.456 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.882           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  320813   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
