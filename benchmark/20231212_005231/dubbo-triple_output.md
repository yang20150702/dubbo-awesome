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
# Warmup Iteration   1: 5.078 ops/ms
# Warmup Iteration   2: 11.782 ops/ms
# Warmup Iteration   3: 12.268 ops/ms
Iteration   1: 12.443 ops/ms
Iteration   2: 12.388 ops/ms
Iteration   3: 12.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.411 ±(99.9%) 0.519 ops/ms [Average]
  (min, avg, max) = (12.388, 12.411, 12.443), stdev = 0.028
  CI (99.9%): [11.892, 12.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ops/ms
# Warmup Iteration   2: 12.919 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 13.079 ops/ms
Iteration   3: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.016 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (12.969, 13.016, 13.079), stdev = 0.057
  CI (99.9%): [11.985, 14.047] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.768 ops/ms
# Warmup Iteration   2: 12.158 ops/ms
# Warmup Iteration   3: 12.506 ops/ms
Iteration   1: 12.667 ops/ms
Iteration   2: 12.703 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.725 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (12.667, 12.725, 12.805), stdev = 0.072
  CI (99.9%): [11.412, 14.038] (assumes normal distribution)


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
# Warmup Iteration   1: 6.482 ops/ms
# Warmup Iteration   2: 10.393 ops/ms
# Warmup Iteration   3: 10.464 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.454 ±(99.9%) 0.775 ops/ms [Average]
  (min, avg, max) = (10.405, 10.454, 10.484), stdev = 0.042
  CI (99.9%): [9.679, 11.229] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.532, 2.559, 2.596), stdev = 0.033
  CI (99.9%): [1.959, 3.159] (assumes normal distribution)


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.484 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.475, 2.484, 2.502), stdev = 0.015
  CI (99.9%): [2.203, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (2.517, 2.536, 2.573), stdev = 0.032
  CI (99.9%): [1.957, 3.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
Iteration   3: 3.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.983, 3.000, 3.014), stdev = 0.016
  CI (99.9%): [2.715, 3.284] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.721 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
Iteration   1: 2.592 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.244 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 12.772 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.582 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.835 ms/op
                 createUser·p0.9999: 11.608 ms/op
                 createUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371758
  mean =      2.580 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 175282 
    [ 2.500,  3.750) = 191191 
    [ 3.750,  5.000) = 4225 
    [ 5.000,  6.250) = 577 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      9.038 ms/op
     p(99.9900) =     13.121 ms/op
     p(99.9990) =     14.769 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.205 ms/op
                 existUser·p0.9999: 13.732 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.276 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  8.415 ms/op
                 existUser·p0.9999: 12.289 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387447
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 190445 
    [ 2.500,  3.750) = 194067 
    [ 3.750,  5.000) = 2176 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.276 ms/op
     p(99.9900) =     13.488 ms/op
     p(99.9990) =     13.851 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  11.620 ms/op
                 getUser·p0.9999: 13.025 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  9.277 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  9.529 ms/op
                 getUser·p0.9999: 11.558 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378822
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 186576 
    [ 2.500,  3.750) = 186328 
    [ 3.750,  5.000) = 4233 
    [ 5.000,  6.250) = 1209 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      9.511 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.602 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.781 ms/op
                 listUser·p0.9999: 12.917 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 13.059 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.657 ms/op
                 listUser·p0.9999: 12.370 ms/op
                 listUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318054
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 92293 
    [ 2.500,  3.750) = 185995 
    [ 3.750,  5.000) = 32207 
    [ 5.000,  6.250) = 5944 
    [ 6.250,  7.500) = 808 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.632 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     12.805 ms/op
     p(99.9990) =     13.582 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.411 ± 0.519  ops/ms
ClientPb.existUser                       thrpt       3  13.016 ± 1.031  ops/ms
ClientPb.getUser                         thrpt       3  12.725 ± 1.313  ops/ms
ClientPb.listUser                        thrpt       3  10.454 ± 0.775  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.600   ms/op
ClientPb.existUser                        avgt       3   2.484 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.579   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.285   ms/op
ClientPb.createUser                     sample  371758   2.580 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.121           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  387447   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.276           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.488           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  378822   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.511           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.763           ms/op
ClientPb.listUser                       sample  318054   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.632           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.805           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
