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
# Warmup Iteration   1: 4.437 ops/ms
# Warmup Iteration   2: 11.549 ops/ms
# Warmup Iteration   3: 12.138 ops/ms
Iteration   1: 12.343 ops/ms
Iteration   2: 12.324 ops/ms
Iteration   3: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.371 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (12.324, 12.371, 12.445), stdev = 0.065
  CI (99.9%): [11.184, 13.557] (assumes normal distribution)


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
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 12.758 ops/ms
# Warmup Iteration   3: 12.786 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.682 ±(99.9%) 3.949 ops/ms [Average]
  (min, avg, max) = (12.437, 12.682, 12.849), stdev = 0.216
  CI (99.9%): [8.733, 16.631] (assumes normal distribution)


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
# Warmup Iteration   1: 7.294 ops/ms
# Warmup Iteration   2: 12.450 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.610 ops/ms
Iteration   2: 12.298 ops/ms
Iteration   3: 12.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.465 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (12.298, 12.465, 12.610), stdev = 0.158
  CI (99.9%): [9.592, 15.338] (assumes normal distribution)


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
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.428 ops/ms
Iteration   1: 10.361 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.376 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (10.324, 10.376, 10.441), stdev = 0.060
  CI (99.9%): [9.285, 11.466] (assumes normal distribution)


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.614 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.003 ms/op
Iteration   2: 2.534 ±(99.9%) 0.003 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.534, 2.546, 2.556), stdev = 0.011
  CI (99.9%): [2.338, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.003 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (2.471, 2.494, 2.519), stdev = 0.024
  CI (99.9%): [2.053, 2.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.530, 2.536, 2.549), stdev = 0.011
  CI (99.9%): [2.340, 2.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
Iteration   3: 3.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (3.047, 3.068, 3.085), stdev = 0.019
  CI (99.9%): [2.715, 3.420] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.741 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  12.170 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.592 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  10.840 ms/op
                 createUser·p0.9999: 14.401 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 2.584 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.945 ms/op
                 createUser·p0.9999: 14.951 ms/op
                 createUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371268
  mean =      2.583 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 175100 
    [ 2.500,  3.750) = 189557 
    [ 3.750,  5.000) = 4714 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     14.318 ms/op
     p(99.9990) =     15.574 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  11.645 ms/op
                 existUser·p0.9999: 15.888 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.642 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  10.462 ms/op
                 existUser·p0.9999: 15.006 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 12.438 ms/op
                 existUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378150
  mean =      2.536 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 179328 
    [ 2.500,  3.750) = 192290 
    [ 3.750,  5.000) = 4426 
    [ 5.000,  6.250) = 928 
    [ 6.250,  7.500) = 429 
    [ 7.500,  8.750) = 169 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 151 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     10.287 ms/op
     p(99.9900) =     15.355 ms/op
     p(99.9990) =     16.537 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.007 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  8.726 ms/op
                 getUser·p0.9999: 14.422 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  11.132 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.076 ms/op
                 getUser·p0.9999: 12.376 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379028
  mean =      2.530 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 184436 
    [ 2.500,  3.750) = 186326 
    [ 3.750,  5.000) = 5854 
    [ 5.000,  6.250) = 1457 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     16.356 ms/op
     p(99.9990) =     18.167 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.873 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.009 ms/op
Iteration   1: 3.111 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.517 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  10.375 ms/op
                 listUser·p0.9999: 12.626 ms/op
                 listUser·p1.00:   14.041 ms/op

Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 11.583 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.969 ms/op
                 listUser·p0.9999: 12.330 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309078
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 79143 
    [ 2.500,  3.750) = 182354 
    [ 3.750,  5.000) = 37431 
    [ 5.000,  6.250) = 7531 
    [ 6.250,  7.500) = 1289 
    [ 7.500,  8.750) = 453 
    [ 8.750, 10.000) = 431 
    [10.000, 11.250) = 250 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     10.124 ms/op
     p(99.9900) =     12.240 ms/op
     p(99.9990) =     13.462 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.371 ± 1.186  ops/ms
ClientPb.existUser                       thrpt       3  12.682 ± 3.949  ops/ms
ClientPb.getUser                         thrpt       3  12.465 ± 2.873  ops/ms
ClientPb.listUser                        thrpt       3  10.376 ± 1.090  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.207   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.441   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.196   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.353   ms/op
ClientPb.createUser                     sample  371268   2.583 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.600           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.318           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.122           ms/op
ClientPb.existUser                      sample  378150   2.536 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.750           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.287           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.355           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.712           ms/op
ClientPb.getUser                        sample  379028   2.530 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.881           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.077           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.356           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.350           ms/op
ClientPb.listUser                       sample  309078   3.103 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.517           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.124           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.240           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.041           ms/op
