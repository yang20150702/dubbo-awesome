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
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 12.142 ops/ms
# Warmup Iteration   3: 12.501 ops/ms
Iteration   1: 12.687 ops/ms
Iteration   2: 12.825 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.764 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (12.687, 12.764, 12.825), stdev = 0.070
  CI (99.9%): [11.483, 14.045] (assumes normal distribution)


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
# Warmup Iteration   1: 8.073 ops/ms
# Warmup Iteration   2: 12.777 ops/ms
# Warmup Iteration   3: 12.895 ops/ms
Iteration   1: 12.822 ops/ms
Iteration   2: 12.978 ops/ms
Iteration   3: 13.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.936 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (12.822, 12.936, 13.008), stdev = 0.100
  CI (99.9%): [11.115, 14.757] (assumes normal distribution)


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
# Warmup Iteration   1: 7.957 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 12.599 ops/ms
Iteration   1: 12.739 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.940 ±(99.9%) 3.314 ops/ms [Average]
  (min, avg, max) = (12.739, 12.940, 13.091), stdev = 0.182
  CI (99.9%): [9.627, 16.254] (assumes normal distribution)


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
# Warmup Iteration   1: 6.940 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 10.658 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.751 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.739 ±(99.9%) 0.185 ops/ms [Average]
  (min, avg, max) = (10.732, 10.739, 10.751), stdev = 0.010
  CI (99.9%): [10.554, 10.924] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.512, 2.533, 2.563), stdev = 0.026
  CI (99.9%): [2.053, 3.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.437, 2.457, 2.481), stdev = 0.023
  CI (99.9%): [2.045, 2.868] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.487, 2.508, 2.531), stdev = 0.022
  CI (99.9%): [2.101, 2.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.984, 3.010, 3.028), stdev = 0.023
  CI (99.9%): [2.594, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.739 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 14.532 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.523 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 15.083 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 13.321 ms/op
                 createUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378647
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 183088 
    [ 2.500,  3.750) = 191994 
    [ 3.750,  5.000) = 2695 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     14.551 ms/op
     p(99.9990) =     15.555 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.006 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.586 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.419 ms/op
                 existUser·p0.999:  6.392 ms/op
                 existUser·p0.9999: 13.364 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  8.759 ms/op
                 existUser·p0.9999: 11.975 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391890
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 195885 
    [ 2.500,  3.750) = 193115 
    [ 3.750,  5.000) = 2158 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.923 ms/op
     p(99.9900) =     15.349 ms/op
     p(99.9990) =     18.101 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 13.654 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  8.342 ms/op
                 getUser·p0.9999: 14.493 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  8.447 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380680
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 188847 
    [ 2.500,  3.750) = 187417 
    [ 3.750,  5.000) = 3543 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.470 ms/op
     p(99.9900) =     13.711 ms/op
     p(99.9990) =     15.194 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
Iteration   1: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 11.330 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 12.051 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.924 ms/op
                 listUser·p0.9999: 11.212 ms/op
                 listUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315182
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 86114 
    [ 2.500,  3.750) = 188261 
    [ 3.750,  5.000) = 33668 
    [ 5.000,  6.250) = 5857 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.772 ms/op
     p(99.9990) =     12.782 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.764 ± 1.281  ops/ms
ClientPb.existUser                       thrpt       3  12.936 ± 1.821  ops/ms
ClientPb.getUser                         thrpt       3  12.940 ± 3.314  ops/ms
ClientPb.listUser                        thrpt       3  10.739 ± 0.185  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.480   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.411   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.407   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.415   ms/op
ClientPb.createUser                     sample  378647   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.856           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.667           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.551           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.696           ms/op
ClientPb.existUser                      sample  391890   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.923           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.349           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.383           ms/op
ClientPb.getUser                        sample  380680   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.693           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.711           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.335           ms/op
ClientPb.listUser                       sample  315182   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.772           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.222           ms/op
