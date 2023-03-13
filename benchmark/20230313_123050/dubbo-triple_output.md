# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.434 ops/ms
# Warmup Iteration   2: 3.485 ops/ms
# Warmup Iteration   3: 7.220 ops/ms
Iteration   1: 7.395 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.904 ±(99.9%) 8.072 ops/ms [Average]
  (min, avg, max) = (7.395, 7.904, 8.195), stdev = 0.442
  CI (99.9%): [≈ 0, 15.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 8.615 ops/ms
Iteration   2: 8.593 ops/ms
Iteration   3: 8.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.611 ±(99.9%) 0.302 ops/ms [Average]
  (min, avg, max) = (8.593, 8.611, 8.625), stdev = 0.017
  CI (99.9%): [8.310, 8.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.022 ops/ms
# Warmup Iteration   2: 6.752 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.786 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.958 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (7.786, 7.958, 8.127), stdev = 0.170
  CI (99.9%): [4.854, 11.061] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.435 ops/ms
# Warmup Iteration   3: 6.592 ops/ms
Iteration   1: 6.521 ops/ms
Iteration   2: 6.686 ops/ms
Iteration   3: 7.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.738 ±(99.9%) 4.504 ops/ms [Average]
  (min, avg, max) = (6.521, 6.738, 7.006), stdev = 0.247
  CI (99.9%): [2.234, 11.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.525 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.757 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.004 ms/op
Iteration   1: 4.174 ±(99.9%) 0.007 ms/op
Iteration   2: 4.064 ±(99.9%) 0.005 ms/op
Iteration   3: 4.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.105 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (4.064, 4.105, 4.174), stdev = 0.060
  CI (99.9%): [3.009, 5.202] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.727 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.005 ms/op
Iteration   1: 3.841 ±(99.9%) 0.008 ms/op
Iteration   2: 3.915 ±(99.9%) 0.005 ms/op
Iteration   3: 3.776 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.844 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (3.776, 3.844, 3.915), stdev = 0.070
  CI (99.9%): [2.574, 5.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.523 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.012 ms/op
Iteration   1: 3.925 ±(99.9%) 0.006 ms/op
Iteration   2: 4.003 ±(99.9%) 0.006 ms/op
Iteration   3: 4.003 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.977 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.925, 3.977, 4.003), stdev = 0.045
  CI (99.9%): [3.156, 4.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.749 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.292 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.013 ms/op
Iteration   1: 4.699 ±(99.9%) 0.010 ms/op
Iteration   2: 4.664 ±(99.9%) 0.007 ms/op
Iteration   3: 4.635 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.666 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (4.635, 4.666, 4.699), stdev = 0.032
  CI (99.9%): [4.077, 5.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.854 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.388 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.606 ±(99.9%) 0.023 ms/op
Iteration   1: 4.094 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 25.248 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 4.031 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  21.480 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 4.071 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  16.341 ms/op
                 createUser·p0.9999: 27.710 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236378
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 219268 
    [ 5.000,  7.500) = 13668 
    [ 7.500, 10.000) = 2398 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     21.813 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.316 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.450 ±(99.9%) 0.015 ms/op
Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.015 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.801 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   33.260 ms/op

Iteration   2: 3.835 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.982 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  25.774 ms/op
                 existUser·p0.9999: 28.377 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  11.687 ms/op
                 existUser·p0.9999: 29.872 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247256
  mean =      3.881 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 236174 
    [ 5.000,  7.500) = 9407 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     16.545 ms/op
     p(99.9900) =     31.204 ms/op
     p(99.9990) =     33.178 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.308 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.012 ms/op
Iteration   1: 4.054 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.040 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   9.648 ms/op
                 getUser·p0.999:  25.988 ms/op
                 getUser·p0.9999: 31.792 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   2: 3.925 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.666 ms/op
                 getUser·p0.999:  12.722 ms/op
                 getUser·p0.9999: 28.646 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  27.714 ms/op
                 getUser·p0.9999: 32.449 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240172
  mean =      3.994 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 229265 
    [ 5.000,  7.500) = 7173 
    [ 7.500, 10.000) = 2641 
    [10.000, 12.500) = 605 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     25.062 ms/op
     p(99.9900) =     31.980 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.818 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.819 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.861 ±(99.9%) 0.020 ms/op
Iteration   1: 4.782 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  26.512 ms/op
                 listUser·p0.9999: 28.506 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 4.503 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.641 ms/op
                 listUser·p0.999:  19.103 ms/op
                 listUser·p0.9999: 25.916 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   3: 4.770 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204966
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 173113 
    [ 5.000,  7.500) = 27065 
    [ 7.500, 10.000) = 3719 
    [10.000, 12.500) = 498 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     19.727 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.904 ± 8.072  ops/ms
ClientPb.existUser                       thrpt       3   8.611 ± 0.302  ops/ms
ClientPb.getUser                         thrpt       3   7.958 ± 3.103  ops/ms
ClientPb.listUser                        thrpt       3   6.738 ± 4.504  ops/ms
ClientPb.createUser                       avgt       3   4.105 ± 1.097   ms/op
ClientPb.existUser                        avgt       3   3.844 ± 1.270   ms/op
ClientPb.getUser                          avgt       3   3.977 ± 0.821   ms/op
ClientPb.listUser                         avgt       3   4.666 ± 0.589   ms/op
ClientPb.createUser                     sample  236378   4.065 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.813           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.132           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.606           ms/op
ClientPb.existUser                      sample  247256   3.881 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.669           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.545           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.260           ms/op
ClientPb.getUser                        sample  240172   3.994 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.585           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.241           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.980           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  204966   4.681 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.727           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.558           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.458           ms/op
