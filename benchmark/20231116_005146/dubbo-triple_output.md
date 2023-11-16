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
# Warmup Iteration   1: 4.733 ops/ms
# Warmup Iteration   2: 11.985 ops/ms
# Warmup Iteration   3: 12.217 ops/ms
Iteration   1: 12.443 ops/ms
Iteration   2: 12.602 ops/ms
Iteration   3: 12.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.593 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (12.443, 12.593, 12.735), stdev = 0.146
  CI (99.9%): [9.926, 15.260] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.752 ops/ms
# Warmup Iteration   2: 12.816 ops/ms
# Warmup Iteration   3: 12.815 ops/ms
Iteration   1: 12.879 ops/ms
Iteration   2: 12.785 ops/ms
Iteration   3: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.798 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (12.731, 12.798, 12.879), stdev = 0.075
  CI (99.9%): [11.429, 14.167] (assumes normal distribution)


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
# Warmup Iteration   1: 7.309 ops/ms
# Warmup Iteration   2: 12.177 ops/ms
# Warmup Iteration   3: 12.601 ops/ms
Iteration   1: 12.586 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.620 ±(99.9%) 2.386 ops/ms [Average]
  (min, avg, max) = (12.510, 12.620, 12.765), stdev = 0.131
  CI (99.9%): [10.234, 15.006] (assumes normal distribution)


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
# Warmup Iteration   1: 6.753 ops/ms
# Warmup Iteration   2: 10.456 ops/ms
# Warmup Iteration   3: 10.593 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.585 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (10.522, 10.585, 10.708), stdev = 0.106
  CI (99.9%): [8.644, 12.526] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.547 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (2.529, 2.547, 2.580), stdev = 0.028
  CI (99.9%): [2.032, 3.063] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.488, 2.496, 2.506), stdev = 0.009
  CI (99.9%): [2.329, 2.662] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.517, 2.539, 2.570), stdev = 0.028
  CI (99.9%): [2.032, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.059 ±(99.9%) 0.005 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (3.047, 3.051, 3.059), stdev = 0.007
  CI (99.9%): [2.921, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  12.532 ms/op
                 createUser·p0.9999: 14.109 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  10.092 ms/op
                 createUser·p0.9999: 13.538 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.553 ms/op
                 createUser·p0.9999: 11.125 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374811
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 177998 
    [ 2.500,  3.750) = 192050 
    [ 3.750,  5.000) = 3960 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      8.839 ms/op
     p(99.9900) =     13.935 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  5.846 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.065 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.447 ms/op
                 existUser·p0.9999: 12.115 ms/op
                 existUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386050
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 189525 
    [ 2.500,  3.750) = 193102 
    [ 3.750,  5.000) = 2549 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.593 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.699 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.523 ms/op
                 getUser·p0.999:  12.294 ms/op
                 getUser·p0.9999: 13.934 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  8.654 ms/op
                 getUser·p0.9999: 11.651 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.707 ms/op
                 getUser·p0.9999: 11.846 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379998
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 187089 
    [ 2.500,  3.750) = 188636 
    [ 3.750,  5.000) = 3226 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.490 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.944 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.010 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  8.953 ms/op
                 listUser·p0.9999: 10.431 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.247 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.700 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 10.885 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312109
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 81762 
    [ 2.500,  3.750) = 186756 
    [ 3.750,  5.000) = 35381 
    [ 5.000,  6.250) = 6592 
    [ 6.250,  7.500) = 823 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 299 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.701 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.593 ± 2.667  ops/ms
ClientPb.existUser                       thrpt       3  12.798 ± 1.369  ops/ms
ClientPb.getUser                         thrpt       3  12.620 ± 2.386  ops/ms
ClientPb.listUser                        thrpt       3  10.585 ± 1.941  ops/ms
ClientPb.createUser                       avgt       3   2.547 ± 0.516   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.507   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.130   ms/op
ClientPb.createUser                     sample  374811   2.559 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.935           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  386050   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.691           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.593           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  379998   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.700           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  312109   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.701           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.682           ms/op
