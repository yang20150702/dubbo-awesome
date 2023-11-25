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
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 12.161 ops/ms
# Warmup Iteration   3: 12.145 ops/ms
Iteration   1: 12.474 ops/ms
Iteration   2: 12.662 ops/ms
Iteration   3: 12.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.578 ±(99.9%) 1.744 ops/ms [Average]
  (min, avg, max) = (12.474, 12.578, 12.662), stdev = 0.096
  CI (99.9%): [10.834, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 8.194 ops/ms
# Warmup Iteration   2: 13.156 ops/ms
# Warmup Iteration   3: 13.134 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 13.099 ops/ms
Iteration   3: 13.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.111 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (13.025, 13.111, 13.208), stdev = 0.092
  CI (99.9%): [11.437, 14.785] (assumes normal distribution)


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
# Warmup Iteration   1: 7.694 ops/ms
# Warmup Iteration   2: 12.779 ops/ms
# Warmup Iteration   3: 12.891 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 13.115 ops/ms
Iteration   3: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.036 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (12.967, 13.036, 13.115), stdev = 0.074
  CI (99.9%): [11.679, 14.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.691 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.678 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.681 ±(99.9%) 0.547 ops/ms [Average]
  (min, avg, max) = (10.646, 10.681, 10.702), stdev = 0.030
  CI (99.9%): [10.133, 11.228] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.003 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (2.491, 2.505, 2.532), stdev = 0.023
  CI (99.9%): [2.087, 2.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.638 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.437, 2.451, 2.467), stdev = 0.015
  CI (99.9%): [2.176, 2.727] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.003 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.477, 2.487, 2.497), stdev = 0.010
  CI (99.9%): [2.305, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
Iteration   3: 2.947 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (2.940, 2.958, 2.985), stdev = 0.024
  CI (99.9%): [2.516, 3.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  10.410 ms/op
                 createUser·p0.9999: 13.557 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 12.146 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  8.229 ms/op
                 createUser·p0.9999: 11.518 ms/op
                 createUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378739
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 182494 
    [ 2.500,  3.750) = 191555 
    [ 3.750,  5.000) = 3581 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.717 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  7.105 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.878 ms/op
                 existUser·p0.9999: 12.981 ms/op
                 existUser·p1.00:   15.516 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  8.242 ms/op
                 existUser·p0.9999: 11.647 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394247
  mean =      2.432 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 201237 
    [ 2.500,  3.750) = 189229 
    [ 3.750,  5.000) = 2685 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.662 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  10.117 ms/op
                 getUser·p0.9999: 13.857 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  7.182 ms/op
                 getUser·p0.9999: 14.894 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.521 ms/op
                 getUser·p0.9999: 10.784 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385580
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 192409 
    [ 2.500,  3.750) = 187172 
    [ 3.750,  5.000) = 4528 
    [ 5.000,  6.250) = 969 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.579 ms/op
     p(99.9900) =     14.039 ms/op
     p(99.9990) =     15.321 ms/op
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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.484 ms/op
                 listUser·p0.999:  10.930 ms/op
                 listUser·p0.9999: 14.550 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.730 ms/op
                 listUser·p0.999:  8.934 ms/op
                 listUser·p0.9999: 11.756 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316471
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 90721 
    [ 2.500,  3.750) = 184545 
    [ 3.750,  5.000) = 33468 
    [ 5.000,  6.250) = 6299 
    [ 6.250,  7.500) = 668 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 158 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.692 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     15.167 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.578 ± 1.744  ops/ms
ClientPb.existUser                       thrpt       3  13.111 ± 1.674  ops/ms
ClientPb.getUser                         thrpt       3  13.036 ± 1.357  ops/ms
ClientPb.listUser                        thrpt       3  10.681 ± 0.547  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.418   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.275   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.181   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.442   ms/op
ClientPb.createUser                     sample  378739   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.728           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.927           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.746           ms/op
ClientPb.existUser                      sample  394247   2.432 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.840           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.516           ms/op
ClientPb.getUser                        sample  385580   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.784           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.579           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.039           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.122           ms/op
ClientPb.listUser                       sample  316471   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.385           ms/op
