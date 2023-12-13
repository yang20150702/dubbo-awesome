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
# Warmup Iteration   1: 5.119 ops/ms
# Warmup Iteration   2: 11.852 ops/ms
# Warmup Iteration   3: 12.169 ops/ms
Iteration   1: 12.204 ops/ms
Iteration   2: 12.557 ops/ms
Iteration   3: 12.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.455 ±(99.9%) 3.990 ops/ms [Average]
  (min, avg, max) = (12.204, 12.455, 12.605), stdev = 0.219
  CI (99.9%): [8.465, 16.446] (assumes normal distribution)


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
# Warmup Iteration   1: 8.553 ops/ms
# Warmup Iteration   2: 13.099 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 12.855 ops/ms
Iteration   2: 13.195 ops/ms
Iteration   3: 13.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.051 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (12.855, 13.051, 13.195), stdev = 0.176
  CI (99.9%): [9.846, 16.256] (assumes normal distribution)


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
# Warmup Iteration   1: 7.614 ops/ms
# Warmup Iteration   2: 12.591 ops/ms
# Warmup Iteration   3: 12.742 ops/ms
Iteration   1: 13.063 ops/ms
Iteration   2: 12.918 ops/ms
Iteration   3: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.990 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (12.918, 12.990, 13.063), stdev = 0.073
  CI (99.9%): [11.667, 14.313] (assumes normal distribution)


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
# Warmup Iteration   1: 6.640 ops/ms
# Warmup Iteration   2: 10.607 ops/ms
# Warmup Iteration   3: 10.553 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.680 ±(99.9%) 0.328 ops/ms [Average]
  (min, avg, max) = (10.663, 10.680, 10.698), stdev = 0.018
  CI (99.9%): [10.352, 11.008] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (2.496, 2.512, 2.533), stdev = 0.019
  CI (99.9%): [2.167, 2.857] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.503 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.486, 2.503, 2.519), stdev = 0.017
  CI (99.9%): [2.202, 2.805] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.470, 2.484, 2.497), stdev = 0.014
  CI (99.9%): [2.233, 2.734] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
Iteration   2: 2.969 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.990 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.969, 2.990, 3.001), stdev = 0.018
  CI (99.9%): [2.657, 3.323] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  10.950 ms/op
                 createUser·p0.9999: 14.226 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.223 ms/op
                 createUser·p0.9999: 12.438 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.132 ms/op
                 createUser·p0.9999: 11.098 ms/op
                 createUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381609
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 183895 
    [ 2.500,  3.750) = 194120 
    [ 3.750,  5.000) = 2910 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.278 ms/op
     p(99.9900) =     13.547 ms/op
     p(99.9990) =     14.509 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.082 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.766 ms/op
                 existUser·p0.9999: 12.339 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  9.648 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386961
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 189177 
    [ 2.500,  3.750) = 194073 
    [ 3.750,  5.000) = 2881 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      6.394 ms/op
     p(99.9900) =     13.014 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  12.112 ms/op
                 getUser·p0.9999: 13.711 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  10.113 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.580 ms/op
                 getUser·p0.9999: 11.796 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374632
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 181351 
    [ 2.500,  3.750) = 187951 
    [ 3.750,  5.000) = 3926 
    [ 5.000,  6.250) = 781 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      9.871 ms/op
     p(99.9900) =     13.526 ms/op
     p(99.9990) =     14.144 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.051 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 12.344 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.051 ms/op
                 listUser·p0.9999: 10.164 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316497
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 89652 
    [ 2.500,  3.750) = 186662 
    [ 3.750,  5.000) = 32308 
    [ 5.000,  6.250) = 6195 
    [ 6.250,  7.500) = 770 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 339 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.065 ms/op
     p(99.9990) =     13.556 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.455 ± 3.990  ops/ms
ClientPb.existUser                       thrpt       3  13.051 ± 3.205  ops/ms
ClientPb.getUser                         thrpt       3  12.990 ± 1.323  ops/ms
ClientPb.listUser                        thrpt       3  10.680 ± 0.328  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.345   ms/op
ClientPb.existUser                        avgt       3   2.503 ± 0.301   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.251   ms/op
ClientPb.listUser                         avgt       3   2.990 ± 0.333   ms/op
ClientPb.createUser                     sample  381609   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.547           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  386961   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.394           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.014           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  374632   2.560 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.871           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.526           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  316497   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.065           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.024           ms/op
