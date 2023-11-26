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
# Warmup Iteration   1: 5.197 ops/ms
# Warmup Iteration   2: 12.073 ops/ms
# Warmup Iteration   3: 12.425 ops/ms
Iteration   1: 12.611 ops/ms
Iteration   2: 12.616 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.682 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (12.611, 12.682, 12.819), stdev = 0.119
  CI (99.9%): [10.519, 14.845] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 8.443 ops/ms
# Warmup Iteration   2: 13.207 ops/ms
# Warmup Iteration   3: 13.020 ops/ms
Iteration   1: 13.177 ops/ms
Iteration   2: 13.268 ops/ms
Iteration   3: 13.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.205 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (13.171, 13.205, 13.268), stdev = 0.054
  CI (99.9%): [12.213, 14.197] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.806 ops/ms
# Warmup Iteration   2: 12.704 ops/ms
# Warmup Iteration   3: 12.865 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.902 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (12.794, 12.902, 12.992), stdev = 0.100
  CI (99.9%): [11.074, 14.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.764 ops/ms
# Warmup Iteration   2: 10.577 ops/ms
# Warmup Iteration   3: 10.769 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.787 ops/ms
Iteration   3: 10.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.729 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (10.667, 10.729, 10.787), stdev = 0.060
  CI (99.9%): [9.633, 11.826] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
Iteration   3: 2.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (2.455, 2.481, 2.501), stdev = 0.023
  CI (99.9%): [2.057, 2.905] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.410 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.406, 2.422, 2.451), stdev = 0.025
  CI (99.9%): [1.970, 2.875] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.003 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.495, 2.502, 2.506), stdev = 0.006
  CI (99.9%): [2.392, 2.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 2.979 ±(99.9%) 0.006 ms/op
Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
Iteration   3: 3.001 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.979, 2.992, 3.001), stdev = 0.011
  CI (99.9%): [2.784, 3.200] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 14.174 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.553 ms/op
                 createUser·p0.999:  7.516 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.904 ms/op
                 createUser·p0.999:  7.695 ms/op
                 createUser·p0.9999: 9.683 ms/op
                 createUser·p1.00:   9.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384840
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186361 
    [ 2.500,  3.750) = 194630 
    [ 3.750,  5.000) = 3126 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     13.673 ms/op
     p(99.9990) =     14.845 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.585 ms/op
                 existUser·p0.999:  5.713 ms/op
                 existUser·p0.9999: 14.402 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  7.401 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.062 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.287 ms/op
                 existUser·p0.9999: 11.351 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391118
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 193938 
    [ 2.500,  3.750) = 193674 
    [ 3.750,  5.000) = 2578 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     13.497 ms/op
     p(99.9990) =     14.900 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.896 ms/op
                 getUser·p0.9999: 14.320 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.772 ms/op
                 getUser·p0.9999: 15.257 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.672 ms/op
                 getUser·p0.9999: 11.304 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383836
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 189610 
    [ 2.500,  3.750) = 188132 
    [ 3.750,  5.000) = 4388 
    [ 5.000,  6.250) = 1143 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      8.670 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     16.043 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.050 ms/op
                 listUser·p0.9999: 13.463 ms/op
                 listUser·p1.00:   14.565 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.014 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.025 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320706
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 180 
    [ 1.250,  2.500) = 96991 
    [ 2.500,  3.750) = 184487 
    [ 3.750,  5.000) = 31774 
    [ 5.000,  6.250) = 6039 
    [ 6.250,  7.500) = 619 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.229 ms/op
     p(99.9900) =     12.613 ms/op
     p(99.9990) =     14.390 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.682 ± 2.163  ops/ms
ClientPb.existUser                       thrpt       3  13.205 ± 0.992  ops/ms
ClientPb.getUser                         thrpt       3  12.902 ± 1.828  ops/ms
ClientPb.listUser                        thrpt       3  10.729 ± 1.097  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.424   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.452   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.110   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.208   ms/op
ClientPb.createUser                     sample  384840   2.492 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.790           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.307           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.122           ms/op
ClientPb.existUser                      sample  391118   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.497           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  383836   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.670           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.122           ms/op
ClientPb.listUser                       sample  320706   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.229           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.613           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.565           ms/op
