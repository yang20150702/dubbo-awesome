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
# Warmup Iteration   1: 4.663 ops/ms
# Warmup Iteration   2: 11.902 ops/ms
# Warmup Iteration   3: 12.299 ops/ms
Iteration   1: 12.473 ops/ms
Iteration   2: 12.629 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.575 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (12.473, 12.575, 12.629), stdev = 0.088
  CI (99.9%): [10.961, 14.189] (assumes normal distribution)


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
# Warmup Iteration   1: 7.447 ops/ms
# Warmup Iteration   2: 12.898 ops/ms
# Warmup Iteration   3: 13.060 ops/ms
Iteration   1: 12.979 ops/ms
Iteration   2: 13.062 ops/ms
Iteration   3: 12.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.999 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (12.955, 12.999, 13.062), stdev = 0.056
  CI (99.9%): [11.971, 14.026] (assumes normal distribution)


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
# Warmup Iteration   1: 7.341 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.866 ops/ms
Iteration   1: 12.857 ops/ms
Iteration   2: 12.852 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 0.408 ops/ms [Average]
  (min, avg, max) = (12.816, 12.842, 12.857), stdev = 0.022
  CI (99.9%): [12.433, 13.250] (assumes normal distribution)


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
# Warmup Iteration   1: 6.515 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (10.477, 10.535, 10.575), stdev = 0.052
  CI (99.9%): [9.589, 11.482] (assumes normal distribution)


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.502, 2.520, 2.536), stdev = 0.017
  CI (99.9%): [2.204, 2.836] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.451, 2.469, 2.495), stdev = 0.023
  CI (99.9%): [2.046, 2.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.547 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.527, 2.547, 2.577), stdev = 0.026
  CI (99.9%): [2.067, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
Iteration   3: 3.028 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.046 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.028, 3.046, 3.063), stdev = 0.018
  CI (99.9%): [2.724, 3.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.673 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  11.086 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.661 ms/op
                 createUser·p0.9999: 13.017 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  8.323 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375963
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 179263 
    [ 2.500,  3.750) = 192022 
    [ 3.750,  5.000) = 3593 
    [ 5.000,  6.250) = 608 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     12.950 ms/op
     p(99.9990) =     13.766 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.990 ms/op
                 existUser·p0.9999: 14.012 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  6.971 ms/op
                 existUser·p0.9999: 13.289 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  6.156 ms/op
                 existUser·p0.9999: 10.945 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388651
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 189539 
    [ 2.500,  3.750) = 195390 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      6.761 ms/op
     p(99.9900) =     13.503 ms/op
     p(99.9990) =     14.657 ms/op
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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  11.867 ms/op
                 getUser·p0.9999: 14.402 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  8.495 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.679 ms/op
                 getUser·p0.9999: 11.491 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382117
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 189045 
    [ 2.500,  3.750) = 186652 
    [ 3.750,  5.000) = 4596 
    [ 5.000,  6.250) = 1303 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      8.608 ms/op
     p(99.9900) =     13.759 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.427 ms/op
                 listUser·p0.9999: 11.622 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.659 ms/op
                 listUser·p0.999:  10.437 ms/op
                 listUser·p0.9999: 13.391 ms/op
                 listUser·p1.00:   14.565 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.758 ms/op
                 listUser·p0.999:  10.304 ms/op
                 listUser·p0.9999: 11.852 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319446
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 93987 
    [ 2.500,  3.750) = 185616 
    [ 3.750,  5.000) = 31892 
    [ 5.000,  6.250) = 6281 
    [ 6.250,  7.500) = 849 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     12.459 ms/op
     p(99.9990) =     13.886 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.575 ± 1.614  ops/ms
ClientPb.existUser                       thrpt       3  12.999 ± 1.028  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 0.408  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 0.946  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.316   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.423   ms/op
ClientPb.getUser                          avgt       3   2.547 ± 0.480   ms/op
ClientPb.listUser                         avgt       3   3.046 ± 0.323   ms/op
ClientPb.createUser                     sample  375963   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.667           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.667           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.950           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  388651   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.761           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.503           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  382117   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.593           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.608           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  319446   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.752           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.961           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.459           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.565           ms/op
