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
# Warmup Iteration   1: 4.876 ops/ms
# Warmup Iteration   2: 11.984 ops/ms
# Warmup Iteration   3: 12.427 ops/ms
Iteration   1: 12.529 ops/ms
Iteration   2: 12.551 ops/ms
Iteration   3: 12.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.596 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (12.529, 12.596, 12.708), stdev = 0.097
  CI (99.9%): [10.819, 14.374] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.341 ops/ms
# Warmup Iteration   2: 12.968 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 13.055 ops/ms
Iteration   3: 13.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.964 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (12.837, 12.964, 13.055), stdev = 0.114
  CI (99.9%): [10.887, 15.042] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 12.644 ops/ms
# Warmup Iteration   3: 12.774 ops/ms
Iteration   1: 12.891 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.855 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (12.806, 12.855, 12.891), stdev = 0.044
  CI (99.9%): [12.046, 13.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.720 ops/ms
# Warmup Iteration   2: 10.623 ops/ms
# Warmup Iteration   3: 10.692 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.730 ±(99.9%) 0.150 ops/ms [Average]
  (min, avg, max) = (10.722, 10.730, 10.739), stdev = 0.008
  CI (99.9%): [10.580, 10.881] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.557 ±(99.9%) 0.003 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (2.508, 2.533, 2.557), stdev = 0.024
  CI (99.9%): [2.089, 2.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
Iteration   3: 2.437 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.437, 2.442, 2.450), stdev = 0.007
  CI (99.9%): [2.305, 2.578] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.443, 2.462, 2.473), stdev = 0.016
  CI (99.9%): [2.163, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.004 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.952, 2.961, 2.968), stdev = 0.008
  CI (99.9%): [2.817, 3.105] (assumes normal distribution)


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 14.292 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.494 ms/op
                 createUser·p0.999:  9.147 ms/op
                 createUser·p0.9999: 12.856 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  9.103 ms/op
                 createUser·p0.9999: 12.173 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381138
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 184357 
    [ 2.500,  3.750) = 193009 
    [ 3.750,  5.000) = 2915 
    [ 5.000,  6.250) = 346 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.835 ms/op
     p(99.9990) =     15.750 ms/op
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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  9.237 ms/op
                 existUser·p0.9999: 14.042 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.673 ms/op
                 existUser·p0.999:  5.841 ms/op
                 existUser·p0.9999: 14.715 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  6.379 ms/op
                 existUser·p0.9999: 10.860 ms/op
                 existUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389380
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 192269 
    [ 2.500,  3.750) = 193536 
    [ 3.750,  5.000) = 2732 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =     13.993 ms/op
     p(99.9990) =     16.726 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  6.279 ms/op
                 getUser·p0.9999: 14.047 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.570 ms/op
                 getUser·p0.9999: 12.861 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  7.388 ms/op
                 getUser·p0.9999: 10.571 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384151
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 190092 
    [ 2.500,  3.750) = 187930 
    [ 3.750,  5.000) = 4779 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      8.026 ms/op
     p(99.9900) =     13.395 ms/op
     p(99.9990) =     14.390 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 9.755 ms/op
                 listUser·p1.00:   10.584 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.239 ms/op
                 listUser·p1.00:   13.812 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.999 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320008
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 94402 
    [ 2.500,  3.750) = 187568 
    [ 3.750,  5.000) = 30974 
    [ 5.000,  6.250) = 5830 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     10.945 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.596 ± 1.777  ops/ms
ClientPb.existUser                       thrpt       3  12.964 ± 2.077  ops/ms
ClientPb.getUser                         thrpt       3  12.855 ± 0.809  ops/ms
ClientPb.listUser                        thrpt       3  10.730 ± 0.150  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.445   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.136   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.299   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.144   ms/op
ClientPb.createUser                     sample  381138   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.897           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.629           ms/op
ClientPb.existUser                      sample  389380   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.993           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.974           ms/op
ClientPb.getUser                        sample  384151   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.026           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.395           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  320008   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.946           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.945           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.812           ms/op
