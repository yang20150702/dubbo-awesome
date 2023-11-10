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
# Warmup Iteration   2: 11.922 ops/ms
# Warmup Iteration   3: 12.361 ops/ms
Iteration   1: 12.389 ops/ms
Iteration   2: 12.390 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.476 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (12.389, 12.476, 12.650), stdev = 0.150
  CI (99.9%): [9.736, 15.216] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.083 ops/ms
# Warmup Iteration   2: 12.753 ops/ms
# Warmup Iteration   3: 12.652 ops/ms
Iteration   1: 12.768 ops/ms
Iteration   2: 12.905 ops/ms
Iteration   3: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.823 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (12.768, 12.823, 12.905), stdev = 0.072
  CI (99.9%): [11.503, 14.144] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.914 ops/ms
# Warmup Iteration   2: 12.341 ops/ms
# Warmup Iteration   3: 12.652 ops/ms
Iteration   1: 12.608 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.614 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (12.574, 12.614, 12.660), stdev = 0.043
  CI (99.9%): [11.827, 13.402] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.547 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (10.477, 10.547, 10.600), stdev = 0.063
  CI (99.9%): [9.391, 11.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.005 ms/op
Iteration   2: 2.578 ±(99.9%) 0.006 ms/op
Iteration   3: 2.557 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.555, 2.564, 2.578), stdev = 0.013
  CI (99.9%): [2.335, 2.792] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.435, 2.455, 2.472), stdev = 0.018
  CI (99.9%): [2.119, 2.792] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.003 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
Iteration   3: 2.550 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.541 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.533, 2.541, 2.550), stdev = 0.008
  CI (99.9%): [2.389, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 2.996 ±(99.9%) 0.004 ms/op
Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.996, 3.006, 3.018), stdev = 0.011
  CI (99.9%): [2.796, 3.215] (assumes normal distribution)


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.818 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 14.039 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  9.019 ms/op
                 createUser·p0.9999: 12.936 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.506 ms/op
                 createUser·p0.9999: 11.721 ms/op
                 createUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378958
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 182495 
    [ 2.500,  3.750) = 192541 
    [ 3.750,  5.000) = 3111 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.572 ms/op
     p(99.9900) =     13.469 ms/op
     p(99.9990) =     14.985 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  8.192 ms/op
                 existUser·p0.9999: 13.527 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 12.951 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381420
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 185439 
    [ 2.500,  3.750) = 191582 
    [ 3.750,  5.000) = 3357 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      7.790 ms/op
     p(99.9900) =     13.646 ms/op
     p(99.9990) =     14.318 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  11.614 ms/op
                 getUser·p0.9999: 13.984 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.476 ms/op
                 getUser·p0.999:  9.724 ms/op
                 getUser·p0.9999: 13.755 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.988 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 11.412 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374009
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 181059 
    [ 2.500,  3.750) = 187219 
    [ 3.750,  5.000) = 4192 
    [ 5.000,  6.250) = 1083 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      9.008 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.339 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.010 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 10.689 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.121 ms/op
                 listUser·p0.9999: 11.562 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316508
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 90541 
    [ 2.500,  3.750) = 185483 
    [ 3.750,  5.000) = 32621 
    [ 5.000,  6.250) = 6480 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.442 ms/op
     p(99.9990) =     11.827 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.476 ± 2.740  ops/ms
ClientPb.existUser                       thrpt       3  12.823 ± 1.320  ops/ms
ClientPb.getUser                         thrpt       3  12.614 ± 0.787  ops/ms
ClientPb.listUser                        thrpt       3  10.547 ± 1.157  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.229   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.337   ms/op
ClientPb.getUser                          avgt       3   2.541 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.209   ms/op
ClientPb.createUser                     sample  378958   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.894           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.572           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.469           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.237           ms/op
ClientPb.existUser                      sample  381420   2.514 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.790           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.646           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  374009   2.564 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  316508   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.442           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
