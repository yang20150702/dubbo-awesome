# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
# Warmup Iteration   2: 12.058 ops/ms
# Warmup Iteration   3: 12.313 ops/ms
Iteration   1: 12.521 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.668 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (12.521, 12.668, 12.765), stdev = 0.129
  CI (99.9%): [10.316, 15.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ops/ms
# Warmup Iteration   2: 12.952 ops/ms
# Warmup Iteration   3: 13.030 ops/ms
Iteration   1: 13.001 ops/ms
Iteration   2: 12.938 ops/ms
Iteration   3: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.997 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (12.938, 12.997, 13.052), stdev = 0.057
  CI (99.9%): [11.963, 14.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.006 ops/ms
# Warmup Iteration   2: 12.403 ops/ms
# Warmup Iteration   3: 12.702 ops/ms
Iteration   1: 12.811 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.720 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (12.642, 12.720, 12.811), stdev = 0.085
  CI (99.9%): [11.162, 14.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.180 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.438 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.567 ±(99.9%) 0.567 ops/ms [Average]
  (min, avg, max) = (10.542, 10.567, 10.602), stdev = 0.031
  CI (99.9%): [10.000, 11.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.003 ms/op
Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
Iteration   3: 2.577 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (2.567, 2.589, 2.623), stdev = 0.030
  CI (99.9%): [2.043, 3.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.458, 2.473, 2.481), stdev = 0.012
  CI (99.9%): [2.246, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.475, 2.492, 2.520), stdev = 0.024
  CI (99.9%): [2.052, 2.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.837 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
Iteration   3: 3.087 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.069 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.051, 3.069, 3.087), stdev = 0.018
  CI (99.9%): [2.741, 3.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  10.563 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.687 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  7.994 ms/op
                 createUser·p0.9999: 10.502 ms/op
                 createUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379723
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 182168 
    [ 2.500,  3.750) = 192620 
    [ 3.750,  5.000) = 3812 
    [ 5.000,  6.250) = 617 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.639 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.009 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  6.933 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.886 ms/op
                 existUser·p0.9999: 14.301 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  9.406 ms/op
                 existUser·p0.9999: 21.275 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389777
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190432 
    [ 2.500,  5.000) = 198402 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  10.529 ms/op
                 getUser·p0.9999: 16.490 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.947 ms/op
                 getUser·p0.999:  7.873 ms/op
                 getUser·p0.9999: 12.652 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.562 ms/op
                 getUser·p0.9999: 11.323 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387128
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 194168 
    [ 2.500,  3.750) = 186717 
    [ 3.750,  5.000) = 4708 
    [ 5.000,  6.250) = 899 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     13.636 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.593 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.009 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.100 ms/op
                 listUser·p0.9999: 10.855 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.915 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.647 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 12.605 ms/op
                 listUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315155
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 85695 
    [ 2.500,  3.750) = 188536 
    [ 3.750,  5.000) = 32988 
    [ 5.000,  6.250) = 6317 
    [ 6.250,  7.500) = 806 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.673 ms/op
     p(99.9990) =     13.088 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.668 ± 2.351  ops/ms
ClientPb.existUser                       thrpt       3  12.997 ± 1.034  ops/ms
ClientPb.getUser                         thrpt       3  12.720 ± 1.559  ops/ms
ClientPb.listUser                        thrpt       3  10.567 ± 0.567  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.547   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.227   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.440   ms/op
ClientPb.listUser                         avgt       3   3.069 ± 0.328   ms/op
ClientPb.createUser                     sample  379723   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.639           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  389777   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.963           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.631           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.643           ms/op
ClientPb.getUser                        sample  387128   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.802           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.636           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.400           ms/op
ClientPb.listUser                       sample  315155   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.812           ms/op
