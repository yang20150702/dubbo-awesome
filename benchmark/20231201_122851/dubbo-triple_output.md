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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 11.494 ops/ms
# Warmup Iteration   3: 12.099 ops/ms
Iteration   1: 12.225 ops/ms
Iteration   2: 12.314 ops/ms
Iteration   3: 12.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.262 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (12.225, 12.262, 12.314), stdev = 0.046
  CI (99.9%): [11.420, 13.104] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.255 ops/ms
# Warmup Iteration   2: 12.935 ops/ms
# Warmup Iteration   3: 12.838 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.785 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (12.706, 12.785, 12.868), stdev = 0.081
  CI (99.9%): [11.303, 14.268] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.573 ops/ms
# Warmup Iteration   2: 12.502 ops/ms
# Warmup Iteration   3: 12.621 ops/ms
Iteration   1: 12.613 ops/ms
Iteration   2: 12.209 ops/ms
Iteration   3: 12.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.401 ±(99.9%) 3.699 ops/ms [Average]
  (min, avg, max) = (12.209, 12.401, 12.613), stdev = 0.203
  CI (99.9%): [8.702, 16.100] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ops/ms
# Warmup Iteration   2: 10.268 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.440 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (10.385, 10.440, 10.493), stdev = 0.054
  CI (99.9%): [9.455, 11.424] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.603 ±(99.9%) 0.005 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (2.516, 2.553, 2.603), stdev = 0.045
  CI (99.9%): [1.739, 3.368] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.417, 2.434, 2.454), stdev = 0.019
  CI (99.9%): [2.095, 2.774] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.003 ms/op
Iteration   1: 2.524 ±(99.9%) 0.003 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (2.505, 2.516, 2.524), stdev = 0.009
  CI (99.9%): [2.345, 2.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.977, 2.987, 3.000), stdev = 0.011
  CI (99.9%): [2.777, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  6.929 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 15.521 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383502
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 184326 
    [ 2.500,  3.750) = 195409 
    [ 3.750,  5.000) = 2901 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     13.249 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.723 ms/op
                 existUser·p0.9999: 13.721 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  5.669 ms/op
                 existUser·p0.9999: 12.813 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  9.426 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386856
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 188013 
    [ 2.500,  3.750) = 195576 
    [ 3.750,  5.000) = 2499 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.621 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     13.912 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.460 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  6.360 ms/op
                 getUser·p0.9999: 16.679 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.901 ms/op
                 getUser·p0.9999: 12.568 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  5.759 ms/op
                 getUser·p0.9999: 10.207 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389075
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 194361 
    [ 2.500,  3.750) = 189826 
    [ 3.750,  5.000) = 3612 
    [ 5.000,  6.250) = 802 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      6.356 ms/op
     p(99.9900) =     14.554 ms/op
     p(99.9990) =     17.218 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.932 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.938 ms/op
                 listUser·p0.9999: 11.104 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.725 ms/op
                 listUser·p0.9999: 13.133 ms/op
                 listUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316987
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 90218 
    [ 2.500,  3.750) = 186494 
    [ 3.750,  5.000) = 32368 
    [ 5.000,  6.250) = 6202 
    [ 6.250,  7.500) = 832 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.903 ms/op
     p(99.9990) =     13.860 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.262 ± 0.842  ops/ms
ClientPb.existUser                       thrpt       3  12.785 ± 1.482  ops/ms
ClientPb.getUser                         thrpt       3  12.401 ± 3.699  ops/ms
ClientPb.listUser                        thrpt       3  10.440 ± 0.985  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.815   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.340   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.171   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.210   ms/op
ClientPb.createUser                     sample  383502   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.710           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.249           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.629           ms/op
ClientPb.existUser                      sample  386856   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.959           ms/op
ClientPb.getUser                        sample  389075   2.466 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.356           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.554           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.465           ms/op
ClientPb.listUser                       sample  316987   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.074           ms/op
