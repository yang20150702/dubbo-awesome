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
# Warmup Iteration   1: 4.870 ops/ms
# Warmup Iteration   2: 11.603 ops/ms
# Warmup Iteration   3: 12.093 ops/ms
Iteration   1: 12.538 ops/ms
Iteration   2: 12.498 ops/ms
Iteration   3: 12.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.470 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (12.375, 12.470, 12.538), stdev = 0.085
  CI (99.9%): [10.924, 14.017] (assumes normal distribution)


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
# Warmup Iteration   1: 7.584 ops/ms
# Warmup Iteration   2: 12.648 ops/ms
# Warmup Iteration   3: 12.628 ops/ms
Iteration   1: 12.817 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 12.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.731 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (12.612, 12.731, 12.817), stdev = 0.106
  CI (99.9%): [10.797, 14.664] (assumes normal distribution)


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
# Warmup Iteration   1: 7.482 ops/ms
# Warmup Iteration   2: 12.176 ops/ms
# Warmup Iteration   3: 12.423 ops/ms
Iteration   1: 12.485 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.522 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (12.470, 12.522, 12.610), stdev = 0.077
  CI (99.9%): [11.121, 13.923] (assumes normal distribution)


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
# Warmup Iteration   1: 6.527 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.253 ops/ms
Iteration   1: 10.326 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.340 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (10.305, 10.340, 10.388), stdev = 0.043
  CI (99.9%): [9.551, 11.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.642 ±(99.9%) 0.005 ms/op
Iteration   1: 2.625 ±(99.9%) 0.004 ms/op
Iteration   2: 2.657 ±(99.9%) 0.005 ms/op
Iteration   3: 2.626 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.636 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.625, 2.636, 2.657), stdev = 0.019
  CI (99.9%): [2.298, 2.974] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.516 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.510, 2.516, 2.524), stdev = 0.007
  CI (99.9%): [2.384, 2.648] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.003 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.590 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.574 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.565, 2.574, 2.590), stdev = 0.014
  CI (99.9%): [2.322, 2.826] (assumes normal distribution)


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.004 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.127 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.100 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.058, 3.100, 3.127), stdev = 0.036
  CI (99.9%): [2.437, 3.763] (assumes normal distribution)


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.753 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.659 ±(99.9%) 0.006 ms/op
Iteration   1: 2.630 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.724 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  12.206 ms/op
                 createUser·p0.9999: 14.137 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.644 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.699 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 17.626 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 2.657 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  9.488 ms/op
                 createUser·p0.9999: 11.976 ms/op
                 createUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 362680
  mean =      2.644 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170093 
    [ 2.500,  5.000) = 191098 
    [ 5.000,  7.500) = 1041 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      9.541 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     19.378 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  5.407 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  9.238 ms/op
                 existUser·p0.9999: 16.089 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.273 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.842 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376986
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181159 
    [ 2.500,  5.000) = 194815 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     21.307 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.616 ±(99.9%) 0.006 ms/op
Iteration   1: 2.621 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  12.714 ms/op
                 getUser·p0.9999: 14.533 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.598 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.183 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  5.710 ms/op
                 getUser·p0.9999: 15.003 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 2.598 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   4.168 ms/op
                 getUser·p0.999:  6.045 ms/op
                 getUser·p0.9999: 12.693 ms/op
                 getUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368049
  mean =      2.606 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 173390 
    [ 2.500,  3.750) = 187736 
    [ 3.750,  5.000) = 5537 
    [ 5.000,  6.250) = 945 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.315 ms/op
     p(99.9900) =     14.421 ms/op
     p(99.9990) =     15.837 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 5.190 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.009 ms/op
Iteration   1: 3.150 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.591 ms/op
                 listUser·p0.9999: 11.197 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.969 ms/op
                 listUser·p0.9999: 12.030 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 3.118 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.510 ms/op
                 listUser·p0.9999: 18.915 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306616
  mean =      3.128 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68980 
    [ 2.500,  5.000) = 229170 
    [ 5.000,  7.500) = 7744 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     10.115 ms/op
     p(99.9900) =     17.731 ms/op
     p(99.9990) =     19.261 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.470 ± 1.547  ops/ms
ClientPb.existUser                       thrpt       3  12.731 ± 1.933  ops/ms
ClientPb.getUser                         thrpt       3  12.522 ± 1.401  ops/ms
ClientPb.listUser                        thrpt       3  10.340 ± 0.789  ops/ms
ClientPb.createUser                       avgt       3   2.636 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   2.516 ± 0.132   ms/op
ClientPb.getUser                          avgt       3   2.574 ± 0.252   ms/op
ClientPb.listUser                         avgt       3   3.100 ± 0.663   ms/op
ClientPb.createUser                     sample  362680   2.644 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.716           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.541           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.282           ms/op
ClientPb.existUser                      sample  376986   2.542 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.283           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.544           ms/op
ClientPb.getUser                        sample  368049   2.606 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.693           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.634           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.421           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.007           ms/op
ClientPb.listUser                       sample  306616   3.128 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.980           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.056           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.115           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.731           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.021           ms/op
