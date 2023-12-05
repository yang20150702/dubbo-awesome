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
# Warmup Iteration   1: 5.121 ops/ms
# Warmup Iteration   2: 12.029 ops/ms
# Warmup Iteration   3: 12.431 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.744 ±(99.9%) 1.437 ops/ms [Average]
  (min, avg, max) = (12.665, 12.744, 12.823), stdev = 0.079
  CI (99.9%): [11.307, 14.182] (assumes normal distribution)


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
# Warmup Iteration   1: 8.535 ops/ms
# Warmup Iteration   2: 13.077 ops/ms
# Warmup Iteration   3: 13.039 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 13.048 ops/ms
Iteration   3: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.958 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (12.769, 12.958, 13.057), stdev = 0.164
  CI (99.9%): [9.971, 15.944] (assumes normal distribution)


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
# Warmup Iteration   1: 7.726 ops/ms
# Warmup Iteration   2: 12.506 ops/ms
# Warmup Iteration   3: 12.749 ops/ms
Iteration   1: 12.873 ops/ms
Iteration   2: 12.809 ops/ms
Iteration   3: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.815 ±(99.9%) 1.017 ops/ms [Average]
  (min, avg, max) = (12.762, 12.815, 12.873), stdev = 0.056
  CI (99.9%): [11.798, 13.832] (assumes normal distribution)


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
# Warmup Iteration   1: 6.400 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.664 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (10.612, 10.664, 10.699), stdev = 0.046
  CI (99.9%): [9.825, 11.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.499, 2.516, 2.539), stdev = 0.021
  CI (99.9%): [2.131, 2.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.452, 2.464, 2.476), stdev = 0.012
  CI (99.9%): [2.242, 2.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.491, 2.516, 2.537), stdev = 0.023
  CI (99.9%): [2.091, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
Iteration   3: 2.995 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.995, 2.999, 3.006), stdev = 0.006
  CI (99.9%): [2.890, 3.108] (assumes normal distribution)


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.725 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.718 ms/op
                 createUser·p0.999:  11.758 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 13.152 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  9.637 ms/op
                 createUser·p0.9999: 12.212 ms/op
                 createUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379301
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 181436 
    [ 2.500,  3.750) = 193317 
    [ 3.750,  5.000) = 3502 
    [ 5.000,  6.250) = 457 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  10.082 ms/op
                 existUser·p0.9999: 13.912 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  9.197 ms/op
                 existUser·p0.9999: 13.254 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 13.878 ms/op
                 existUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389240
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 191301 
    [ 2.500,  3.750) = 194300 
    [ 3.750,  5.000) = 2785 
    [ 5.000,  6.250) = 328 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     15.599 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  5.921 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  9.879 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.377 ms/op
                 getUser·p0.9999: 11.571 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384143
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 191127 
    [ 2.500,  3.750) = 186780 
    [ 3.750,  5.000) = 4923 
    [ 5.000,  6.250) = 784 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.102 ms/op
     p(99.9000) =      7.253 ms/op
     p(99.9900) =     13.610 ms/op
     p(99.9990) =     14.928 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.944 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.067 ms/op
                 listUser·p0.9999: 10.405 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 12.670 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316270
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 88789 
    [ 2.500,  3.750) = 186366 
    [ 3.750,  5.000) = 33570 
    [ 5.000,  6.250) = 6114 
    [ 6.250,  7.500) = 663 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     13.075 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.744 ± 1.437  ops/ms
ClientPb.existUser                       thrpt       3  12.958 ± 2.987  ops/ms
ClientPb.getUser                         thrpt       3  12.815 ± 1.017  ops/ms
ClientPb.listUser                        thrpt       3  10.664 ± 0.838  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.425   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.109   ms/op
ClientPb.createUser                     sample  379301   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.650           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  389240   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.961           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.684           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.745           ms/op
ClientPb.getUser                        sample  384143   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.854           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.102           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.253           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.942           ms/op
ClientPb.listUser                       sample  316270   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.891           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
