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
# Warmup Iteration   1: 5.179 ops/ms
# Warmup Iteration   2: 11.870 ops/ms
# Warmup Iteration   3: 12.320 ops/ms
Iteration   1: 12.313 ops/ms
Iteration   2: 12.564 ops/ms
Iteration   3: 12.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.477 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (12.313, 12.477, 12.564), stdev = 0.142
  CI (99.9%): [9.894, 15.059] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.046 ops/ms
# Warmup Iteration   2: 13.078 ops/ms
# Warmup Iteration   3: 13.102 ops/ms
Iteration   1: 12.989 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.021 ±(99.9%) 0.631 ops/ms [Average]
  (min, avg, max) = (12.989, 13.021, 13.058), stdev = 0.035
  CI (99.9%): [12.390, 13.652] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.079 ops/ms
# Warmup Iteration   2: 12.673 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 12.819 ops/ms
Iteration   3: 12.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.886 ±(99.9%) 1.359 ops/ms [Average]
  (min, avg, max) = (12.819, 12.886, 12.967), stdev = 0.074
  CI (99.9%): [11.528, 14.245] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.569 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 10.567 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.576 ±(99.9%) 0.147 ops/ms [Average]
  (min, avg, max) = (10.566, 10.576, 10.581), stdev = 0.008
  CI (99.9%): [10.429, 10.722] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.003 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.503 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.494, 2.503, 2.510), stdev = 0.008
  CI (99.9%): [2.353, 2.653] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.401, 2.424, 2.440), stdev = 0.020
  CI (99.9%): [2.052, 2.797] (assumes normal distribution)


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.003 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.490, 2.506, 2.520), stdev = 0.015
  CI (99.9%): [2.225, 2.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.031 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (3.025, 3.031, 3.040), stdev = 0.008
  CI (99.9%): [2.882, 3.179] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 13.367 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.569 ms/op
                 createUser·p0.9999: 11.669 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.086 ms/op
                 createUser·p0.9999: 10.139 ms/op
                 createUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383123
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 185035 
    [ 2.500,  3.750) = 193931 
    [ 3.750,  5.000) = 3161 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.796 ms/op
     p(99.9900) =     12.753 ms/op
     p(99.9990) =     13.601 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  9.086 ms/op
                 existUser·p0.9999: 15.062 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.500 ms/op
                 existUser·p0.999:  5.804 ms/op
                 existUser·p0.9999: 15.975 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  9.636 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386571
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189626 
    [ 2.500,  3.750) = 194055 
    [ 3.750,  5.000) = 2216 
    [ 5.000,  6.250) = 202 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      8.277 ms/op
     p(99.9900) =     15.210 ms/op
     p(99.9990) =     16.353 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.222 ms/op
                 getUser·p0.9999: 13.906 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  10.281 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  7.763 ms/op
                 getUser·p0.9999: 10.994 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382516
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188720 
    [ 2.500,  5.000) = 192941 
    [ 5.000,  7.500) = 467 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     14.741 ms/op
     p(99.9990) =     21.370 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 14.030 ms/op
                 listUser·p1.00:   14.451 ms/op

Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.506 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 13.383 ms/op
                 listUser·p1.00:   14.320 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 11.483 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317024
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 86065 
    [ 2.500,  3.750) = 192242 
    [ 3.750,  5.000) = 31979 
    [ 5.000,  6.250) = 5337 
    [ 6.250,  7.500) = 601 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.544 ms/op
     p(99.9000) =      9.584 ms/op
     p(99.9900) =     12.907 ms/op
     p(99.9990) =     14.360 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.477 ± 2.583  ops/ms
ClientPb.existUser                       thrpt       3  13.021 ± 0.631  ops/ms
ClientPb.getUser                         thrpt       3  12.886 ± 1.359  ops/ms
ClientPb.listUser                        thrpt       3  10.576 ± 0.147  ops/ms
ClientPb.createUser                       avgt       3   2.503 ± 0.150   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.372   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.281   ms/op
ClientPb.listUser                         avgt       3   3.031 ± 0.149   ms/op
ClientPb.createUser                     sample  383123   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.796           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.753           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.713           ms/op
ClientPb.existUser                      sample  386571   2.481 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.277           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.210           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.466           ms/op
ClientPb.getUser                        sample  382516   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.702           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.741           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.529           ms/op
ClientPb.listUser                       sample  317024   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.544           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.584           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.907           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.451           ms/op
