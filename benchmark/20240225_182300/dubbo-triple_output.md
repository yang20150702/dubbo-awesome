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
# Warmup Iteration   1: 4.787 ops/ms
# Warmup Iteration   2: 12.184 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.644 ops/ms
Iteration   2: 12.723 ops/ms
Iteration   3: 12.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.724 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (12.644, 12.724, 12.806), stdev = 0.081
  CI (99.9%): [11.250, 14.199] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ops/ms
# Warmup Iteration   2: 13.256 ops/ms
# Warmup Iteration   3: 13.175 ops/ms
Iteration   1: 13.424 ops/ms
Iteration   2: 13.122 ops/ms
Iteration   3: 13.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.190 ±(99.9%) 3.813 ops/ms [Average]
  (min, avg, max) = (13.023, 13.190, 13.424), stdev = 0.209
  CI (99.9%): [9.376, 17.003] (assumes normal distribution)


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
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 12.633 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 13.107 ops/ms
Iteration   2: 13.163 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.100 ±(99.9%) 1.224 ops/ms [Average]
  (min, avg, max) = (13.029, 13.100, 13.163), stdev = 0.067
  CI (99.9%): [11.875, 14.324] (assumes normal distribution)


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
# Warmup Iteration   1: 7.213 ops/ms
# Warmup Iteration   2: 10.604 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.795 ±(99.9%) 0.262 ops/ms [Average]
  (min, avg, max) = (10.778, 10.795, 10.804), stdev = 0.014
  CI (99.9%): [10.533, 11.056] (assumes normal distribution)


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.468 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.439, 2.468, 2.504), stdev = 0.033
  CI (99.9%): [1.868, 3.068] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.003 ms/op
Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.422, 2.431, 2.440), stdev = 0.009
  CI (99.9%): [2.266, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.003 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (2.460, 2.481, 2.517), stdev = 0.032
  CI (99.9%): [1.898, 3.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.004 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.004 ms/op
Iteration   3: 3.003 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (2.956, 2.982, 3.003), stdev = 0.024
  CI (99.9%): [2.539, 3.426] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.244 ms/op
                 createUser·p0.9999: 13.408 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 12.166 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  10.229 ms/op
                 createUser·p0.9999: 15.947 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374591
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 177650 
    [ 2.500,  3.750) = 192740 
    [ 3.750,  5.000) = 3175 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      9.821 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     17.703 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
Iteration   1: 2.396 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  5.584 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 12.335 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 11.805 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396576
  mean =      2.418 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 197244 
    [ 2.500,  3.750) = 196185 
    [ 3.750,  5.000) = 2213 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.683 ms/op
     p(99.9900) =     12.807 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  11.296 ms/op
                 getUser·p0.9999: 13.374 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 12.534 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  8.095 ms/op
                 getUser·p0.9999: 11.698 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380883
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 188380 
    [ 2.500,  3.750) = 187880 
    [ 3.750,  5.000) = 3664 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.008 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.635 ms/op
                 listUser·p0.999:  9.165 ms/op
                 listUser·p0.9999: 11.480 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.210 ms/op
                 listUser·p0.9999: 10.650 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.532 ms/op
                 listUser·p0.9999: 12.035 ms/op
                 listUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320619
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 98009 
    [ 2.500,  3.750) = 183812 
    [ 3.750,  5.000) = 31372 
    [ 5.000,  6.250) = 5870 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.533 ms/op
     p(99.9990) =     12.393 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.724 ± 1.475  ops/ms
ClientPb.existUser                       thrpt       3  13.190 ± 3.813  ops/ms
ClientPb.getUser                         thrpt       3  13.100 ± 1.224  ops/ms
ClientPb.listUser                        thrpt       3  10.795 ± 0.262  ops/ms
ClientPb.createUser                       avgt       3   2.468 ± 0.600   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.164   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.582   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.444   ms/op
ClientPb.createUser                     sample  374591   2.561 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.821           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.123           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.235           ms/op
ClientPb.existUser                      sample  396576   2.418 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.955           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.683           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.317           ms/op
ClientPb.getUser                        sample  380883   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.481           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.667           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.171           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.500           ms/op
ClientPb.listUser                       sample  320619   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.533           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
