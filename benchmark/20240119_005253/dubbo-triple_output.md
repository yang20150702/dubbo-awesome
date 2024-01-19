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
# Warmup Iteration   1: 4.694 ops/ms
# Warmup Iteration   2: 12.057 ops/ms
# Warmup Iteration   3: 12.142 ops/ms
Iteration   1: 12.394 ops/ms
Iteration   2: 12.388 ops/ms
Iteration   3: 12.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.407 ±(99.9%) 0.516 ops/ms [Average]
  (min, avg, max) = (12.388, 12.407, 12.439), stdev = 0.028
  CI (99.9%): [11.891, 12.922] (assumes normal distribution)


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
# Warmup Iteration   1: 8.116 ops/ms
# Warmup Iteration   2: 12.861 ops/ms
# Warmup Iteration   3: 12.922 ops/ms
Iteration   1: 13.028 ops/ms
Iteration   2: 12.936 ops/ms
Iteration   3: 12.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.898 ±(99.9%) 2.784 ops/ms [Average]
  (min, avg, max) = (12.730, 12.898, 13.028), stdev = 0.153
  CI (99.9%): [10.114, 15.682] (assumes normal distribution)


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
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 12.441 ops/ms
# Warmup Iteration   3: 12.584 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.726 ops/ms
Iteration   3: 12.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.753 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (12.726, 12.753, 12.770), stdev = 0.024
  CI (99.9%): [12.315, 13.191] (assumes normal distribution)


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
# Warmup Iteration   1: 6.547 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.394 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.461 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (10.394, 10.461, 10.531), stdev = 0.069
  CI (99.9%): [9.203, 11.719] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.005 ms/op
Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.544, 2.558, 2.571), stdev = 0.014
  CI (99.9%): [2.304, 2.813] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.003 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.481 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.478, 2.481, 2.485), stdev = 0.004
  CI (99.9%): [2.414, 2.549] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.543 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.533, 2.543, 2.560), stdev = 0.015
  CI (99.9%): [2.275, 2.811] (assumes normal distribution)


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
Iteration   3: 3.053 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.060 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.053, 3.060, 3.064), stdev = 0.006
  CI (99.9%): [2.952, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 13.539 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  9.280 ms/op
                 createUser·p0.9999: 13.161 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.833 ms/op
                 createUser·p0.999:  8.439 ms/op
                 createUser·p0.9999: 10.557 ms/op
                 createUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379900
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 183802 
    [ 2.500,  3.750) = 191887 
    [ 3.750,  5.000) = 3391 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.621 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.508 ms/op
                 existUser·p0.9999: 13.419 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  9.578 ms/op
                 existUser·p0.9999: 11.272 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386167
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188881 
    [ 2.500,  3.750) = 193642 
    [ 3.750,  5.000) = 2856 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.046 ms/op
     p(99.9900) =     13.310 ms/op
     p(99.9990) =     13.816 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 13.179 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  10.169 ms/op
                 getUser·p0.9999: 12.625 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.213 ms/op
                 getUser·p0.9999: 11.982 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378339
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 184731 
    [ 2.500,  3.750) = 186153 
    [ 3.750,  5.000) = 5740 
    [ 5.000,  6.250) = 1160 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.410 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     13.807 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.009 ms/op
Iteration   1: 3.093 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.922 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.092 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.813 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310284
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 77066 
    [ 2.500,  3.750) = 187892 
    [ 3.750,  5.000) = 37067 
    [ 5.000,  6.250) = 6647 
    [ 6.250,  7.500) = 854 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.830 ms/op
     p(99.9990) =     11.664 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.407 ± 0.516  ops/ms
ClientPb.existUser                       thrpt       3  12.898 ± 2.784  ops/ms
ClientPb.getUser                         thrpt       3  12.753 ± 0.438  ops/ms
ClientPb.listUser                        thrpt       3  10.461 ± 1.258  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.255   ms/op
ClientPb.existUser                        avgt       3   2.481 ± 0.068   ms/op
ClientPb.getUser                          avgt       3   2.543 ± 0.268   ms/op
ClientPb.listUser                         avgt       3   3.060 ± 0.108   ms/op
ClientPb.createUser                     sample  379900   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.621           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  386167   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.046           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.310           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  378339   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.410           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.025           ms/op
ClientPb.listUser                       sample  310284   3.091 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.830           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.764           ms/op
