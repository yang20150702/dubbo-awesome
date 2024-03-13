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
# Warmup Iteration   1: 5.118 ops/ms
# Warmup Iteration   2: 12.065 ops/ms
# Warmup Iteration   3: 12.277 ops/ms
Iteration   1: 12.519 ops/ms
Iteration   2: 12.531 ops/ms
Iteration   3: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.584 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (12.519, 12.584, 12.701), stdev = 0.102
  CI (99.9%): [10.724, 14.444] (assumes normal distribution)


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
# Warmup Iteration   1: 8.139 ops/ms
# Warmup Iteration   2: 12.818 ops/ms
# Warmup Iteration   3: 13.049 ops/ms
Iteration   1: 12.890 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.924 ±(99.9%) 0.721 ops/ms [Average]
  (min, avg, max) = (12.890, 12.924, 12.967), stdev = 0.040
  CI (99.9%): [12.202, 13.645] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.968 ops/ms
# Warmup Iteration   2: 12.479 ops/ms
# Warmup Iteration   3: 12.863 ops/ms
Iteration   1: 12.930 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.875 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (12.796, 12.875, 12.930), stdev = 0.070
  CI (99.9%): [11.596, 14.154] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.547 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.524 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (10.476, 10.524, 10.573), stdev = 0.048
  CI (99.9%): [9.641, 11.406] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.509, 2.533, 2.548), stdev = 0.021
  CI (99.9%): [2.145, 2.921] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.003 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (2.413, 2.446, 2.478), stdev = 0.032
  CI (99.9%): [1.858, 3.035] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.470, 2.492, 2.515), stdev = 0.023
  CI (99.9%): [2.080, 2.904] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.005 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
Iteration   3: 3.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.058 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.039, 3.058, 3.088), stdev = 0.026
  CI (99.9%): [2.582, 3.534] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  11.385 ms/op
                 createUser·p0.9999: 13.790 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  9.364 ms/op
                 createUser·p0.9999: 12.065 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.594 ms/op
                 createUser·p0.9999: 11.084 ms/op
                 createUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380385
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 185008 
    [ 2.500,  3.750) = 190823 
    [ 3.750,  5.000) = 3689 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.759 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.162 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  6.207 ms/op
                 existUser·p0.9999: 14.416 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.266 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 11.584 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390822
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 192289 
    [ 2.500,  3.750) = 195433 
    [ 3.750,  5.000) = 2341 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.021 ms/op
     p(99.9900) =     13.711 ms/op
     p(99.9990) =     14.688 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  7.632 ms/op
                 getUser·p0.9999: 13.484 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  9.775 ms/op
                 getUser·p0.9999: 13.437 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 11.108 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385031
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 190384 
    [ 2.500,  3.750) = 189831 
    [ 3.750,  5.000) = 3807 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     13.859 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
Iteration   1: 3.098 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.024 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.723 ms/op
                 listUser·p0.999:  9.700 ms/op
                 listUser·p0.9999: 11.492 ms/op
                 listUser·p1.00:   13.255 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.220 ms/op
                 listUser·p0.9999: 10.728 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311276
  mean =      3.081 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 80478 
    [ 2.500,  3.750) = 185719 
    [ 3.750,  5.000) = 36593 
    [ 5.000,  6.250) = 6872 
    [ 6.250,  7.500) = 868 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     12.546 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.584 ± 1.860  ops/ms
ClientPb.existUser                       thrpt       3  12.924 ± 0.721  ops/ms
ClientPb.getUser                         thrpt       3  12.875 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3  10.524 ± 0.883  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.588   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.412   ms/op
ClientPb.listUser                         avgt       3   3.058 ± 0.476   ms/op
ClientPb.createUser                     sample  380385   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  390822   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.711           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.926           ms/op
ClientPb.getUser                        sample  385031   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.919           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.437           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  311276   3.081 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.913           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
