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
# Warmup Iteration   1: 4.688 ops/ms
# Warmup Iteration   2: 11.879 ops/ms
# Warmup Iteration   3: 12.462 ops/ms
Iteration   1: 12.641 ops/ms
Iteration   2: 12.704 ops/ms
Iteration   3: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.704 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.641, 12.704, 12.769), stdev = 0.064
  CI (99.9%): [11.542, 13.867] (assumes normal distribution)


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
# Warmup Iteration   1: 8.382 ops/ms
# Warmup Iteration   2: 12.998 ops/ms
# Warmup Iteration   3: 13.088 ops/ms
Iteration   1: 13.248 ops/ms
Iteration   2: 13.215 ops/ms
Iteration   3: 13.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.199 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (13.134, 13.199, 13.248), stdev = 0.058
  CI (99.9%): [12.135, 14.263] (assumes normal distribution)


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
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 12.645 ops/ms
# Warmup Iteration   3: 12.677 ops/ms
Iteration   1: 12.811 ops/ms
Iteration   2: 12.617 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.778 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (12.617, 12.778, 12.906), stdev = 0.147
  CI (99.9%): [10.088, 15.467] (assumes normal distribution)


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
# Warmup Iteration   1: 6.699 ops/ms
# Warmup Iteration   2: 10.559 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.778 ops/ms
Iteration   2: 10.748 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.733 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (10.672, 10.733, 10.778), stdev = 0.054
  CI (99.9%): [9.740, 11.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.521, 2.531, 2.546), stdev = 0.013
  CI (99.9%): [2.291, 2.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.420, 2.443, 2.461), stdev = 0.021
  CI (99.9%): [2.056, 2.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
Iteration   1: 2.560 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.559 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (2.551, 2.559, 2.565), stdev = 0.007
  CI (99.9%): [2.423, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 2.995 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.995, 3.008, 3.024), stdev = 0.015
  CI (99.9%): [2.739, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  11.603 ms/op
                 createUser·p0.9999: 14.128 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 11.863 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.809 ms/op
                 createUser·p0.9999: 10.748 ms/op
                 createUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381542
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 184327 
    [ 2.500,  3.750) = 193949 
    [ 3.750,  5.000) = 2526 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     13.069 ms/op
     p(99.9990) =     14.503 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.729 ms/op
                 existUser·p0.999:  5.632 ms/op
                 existUser·p0.9999: 14.045 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.571 ms/op
                 existUser·p0.9999: 14.920 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388485
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 191396 
    [ 2.500,  3.750) = 193763 
    [ 3.750,  5.000) = 2516 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.983 ms/op
     p(99.9900) =     14.125 ms/op
     p(99.9990) =     15.501 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 13.944 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.439 ms/op
                 getUser·p0.9999: 17.144 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  7.010 ms/op
                 getUser·p0.9999: 11.666 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387273
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 193434 
    [ 2.500,  3.750) = 188716 
    [ 3.750,  5.000) = 4085 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      6.493 ms/op
     p(99.9900) =     14.062 ms/op
     p(99.9990) =     17.375 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.605 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.591 ms/op
                 listUser·p0.9999: 12.192 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.279 ms/op
                 listUser·p0.9999: 11.217 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322728
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 97655 
    [ 2.500,  3.750) = 188019 
    [ 3.750,  5.000) = 30430 
    [ 5.000,  6.250) = 5350 
    [ 6.250,  7.500) = 504 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 321 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.149 ms/op
     p(99.9990) =     12.641 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.704 ± 1.163  ops/ms
ClientPb.existUser                       thrpt       3  13.199 ± 1.064  ops/ms
ClientPb.getUser                         thrpt       3  12.778 ± 2.690  ops/ms
ClientPb.listUser                        thrpt       3  10.733 ± 0.993  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.387   ms/op
ClientPb.getUser                          avgt       3   2.559 ± 0.135   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.269   ms/op
ClientPb.createUser                     sample  381542   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.069           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  388485   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.983           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.125           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.679           ms/op
ClientPb.getUser                        sample  387273   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.859           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.493           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.957           ms/op
ClientPb.listUser                       sample  322728   2.972 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.149           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
