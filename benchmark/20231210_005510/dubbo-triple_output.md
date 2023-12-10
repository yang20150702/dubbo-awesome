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
# Warmup Iteration   1: 4.711 ops/ms
# Warmup Iteration   2: 12.267 ops/ms
# Warmup Iteration   3: 12.484 ops/ms
Iteration   1: 12.503 ops/ms
Iteration   2: 12.819 ops/ms
Iteration   3: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.738 ±(99.9%) 3.758 ops/ms [Average]
  (min, avg, max) = (12.503, 12.738, 12.890), stdev = 0.206
  CI (99.9%): [8.980, 16.496] (assumes normal distribution)


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
# Warmup Iteration   1: 8.346 ops/ms
# Warmup Iteration   2: 13.087 ops/ms
# Warmup Iteration   3: 13.010 ops/ms
Iteration   1: 13.133 ops/ms
Iteration   2: 13.040 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.064 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (13.018, 13.064, 13.133), stdev = 0.061
  CI (99.9%): [11.955, 14.172] (assumes normal distribution)


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
# Warmup Iteration   1: 7.520 ops/ms
# Warmup Iteration   2: 12.567 ops/ms
# Warmup Iteration   3: 12.715 ops/ms
Iteration   1: 12.781 ops/ms
Iteration   2: 12.842 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (12.781, 12.842, 12.904), stdev = 0.062
  CI (99.9%): [11.719, 13.966] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.617 ops/ms
# Warmup Iteration   2: 10.646 ops/ms
# Warmup Iteration   3: 10.706 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.723 ±(99.9%) 0.277 ops/ms [Average]
  (min, avg, max) = (10.706, 10.723, 10.734), stdev = 0.015
  CI (99.9%): [10.446, 11.000] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.470, 2.497, 2.517), stdev = 0.025
  CI (99.9%): [2.048, 2.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.441, 2.448, 2.456), stdev = 0.008
  CI (99.9%): [2.303, 2.592] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.516, 2.531, 2.538), stdev = 0.013
  CI (99.9%): [2.302, 2.759] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.010, 3.015, 3.023), stdev = 0.007
  CI (99.9%): [2.888, 3.142] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  10.785 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  7.423 ms/op
                 createUser·p0.9999: 12.651 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.623 ms/op
                 createUser·p0.9999: 11.600 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382970
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 184304 
    [ 2.500,  3.750) = 194486 
    [ 3.750,  5.000) = 3197 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.635 ms/op
     p(99.9900) =     15.051 ms/op
     p(99.9990) =     19.371 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 13.272 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.550 ms/op
                 existUser·p0.999:  6.678 ms/op
                 existUser·p0.9999: 13.768 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388531
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189432 
    [ 2.500,  3.750) = 195563 
    [ 3.750,  5.000) = 2552 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 151 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.677 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.227 ms/op
     p(99.9990) =     14.623 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  10.842 ms/op
                 getUser·p0.9999: 13.693 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.570 ms/op
                 getUser·p0.9999: 12.452 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  7.071 ms/op
                 getUser·p0.9999: 12.571 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383693
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 189673 
    [ 2.500,  3.750) = 188977 
    [ 3.750,  5.000) = 4115 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 157 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.564 ms/op
     p(99.9900) =     13.052 ms/op
     p(99.9990) =     14.314 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.523 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.235 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 11.261 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.986 ms/op
                 listUser·p0.9999: 12.032 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319452
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 93247 
    [ 2.500,  3.750) = 187669 
    [ 3.750,  5.000) = 31695 
    [ 5.000,  6.250) = 5490 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.601 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.738 ± 3.758  ops/ms
ClientPb.existUser                       thrpt       3  13.064 ± 1.109  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 1.124  ops/ms
ClientPb.listUser                        thrpt       3  10.723 ± 0.277  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.450   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.144   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.127   ms/op
ClientPb.createUser                     sample  382970   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.635           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.595           ms/op
ClientPb.existUser                      sample  388531   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.677           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.909           ms/op
ClientPb.getUser                        sample  383693   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.052           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.352           ms/op
ClientPb.listUser                       sample  319452   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.523           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.601           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
