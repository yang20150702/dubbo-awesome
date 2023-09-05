# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 4.336 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 8.176 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.355 ±(99.9%) 3.075 ops/ms [Average]
  (min, avg, max) = (8.176, 8.355, 8.511), stdev = 0.169
  CI (99.9%): [5.281, 11.430] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.579 ops/ms
# Warmup Iteration   2: 7.440 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.512 ±(99.9%) 4.920 ops/ms [Average]
  (min, avg, max) = (8.342, 8.512, 8.823), stdev = 0.270
  CI (99.9%): [3.592, 13.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.402 ops/ms
# Warmup Iteration   2: 6.858 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.250 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (8.212, 8.250, 8.316), stdev = 0.058
  CI (99.9%): [7.194, 9.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 6.244 ops/ms
# Warmup Iteration   3: 6.849 ops/ms
Iteration   1: 6.964 ops/ms
Iteration   2: 7.225 ops/ms
Iteration   3: 7.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.081 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (6.964, 7.081, 7.225), stdev = 0.133
  CI (99.9%): [4.663, 9.498] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.711 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.005 ms/op
Iteration   1: 4.032 ±(99.9%) 0.007 ms/op
Iteration   2: 3.951 ±(99.9%) 0.007 ms/op
Iteration   3: 3.802 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.928 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.802, 3.928, 4.032), stdev = 0.117
  CI (99.9%): [1.799, 6.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.860 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.005 ms/op
Iteration   1: 3.763 ±(99.9%) 0.004 ms/op
Iteration   2: 3.748 ±(99.9%) 0.005 ms/op
Iteration   3: 3.660 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.724 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (3.660, 3.724, 3.763), stdev = 0.056
  CI (99.9%): [2.711, 4.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.020 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.004 ms/op
Iteration   1: 4.087 ±(99.9%) 0.004 ms/op
Iteration   2: 4.052 ±(99.9%) 0.009 ms/op
Iteration   3: 3.833 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.991 ±(99.9%) 2.512 ms/op [Average]
  (min, avg, max) = (3.833, 3.991, 4.087), stdev = 0.138
  CI (99.9%): [1.479, 6.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.349 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.007 ms/op
Iteration   1: 4.646 ±(99.9%) 0.011 ms/op
Iteration   2: 4.455 ±(99.9%) 0.013 ms/op
Iteration   3: 4.569 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.556 ±(99.9%) 1.745 ms/op [Average]
  (min, avg, max) = (4.455, 4.556, 4.646), stdev = 0.096
  CI (99.9%): [2.811, 6.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.904 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.017 ms/op
Iteration   1: 4.042 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  22.905 ms/op
                 createUser·p0.9999: 25.788 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.883 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.806 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  25.113 ms/op
                 createUser·p0.9999: 29.165 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  15.565 ms/op
                 createUser·p0.9999: 35.127 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243527
  mean =      3.940 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 366 
    [ 2.500,  5.000) = 229853 
    [ 5.000,  7.500) = 10713 
    [ 7.500, 10.000) = 1734 
    [10.000, 12.500) = 481 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.690 ms/op
     p(99.9000) =     22.822 ms/op
     p(99.9900) =     32.602 ms/op
     p(99.9990) =     35.689 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.798 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.013 ms/op
Iteration   1: 3.852 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 26.732 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 3.893 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  19.759 ms/op
                 existUser·p0.9999: 32.688 ms/op
                 existUser·p1.00:   33.227 ms/op

Iteration   3: 3.681 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  28.700 ms/op
                 existUser·p0.9999: 32.778 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252042
  mean =      3.807 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1285 
    [ 2.500,  5.000) = 235400 
    [ 5.000,  7.500) = 12908 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 561 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 79 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.217 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     32.637 ms/op
     p(99.9990) =     33.258 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.221 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.016 ms/op
Iteration   1: 4.020 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  22.199 ms/op
                 getUser·p0.9999: 29.525 ms/op
                 getUser·p1.00:   31.850 ms/op

Iteration   2: 3.959 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.960 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  24.543 ms/op
                 getUser·p0.9999: 26.832 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.940 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.981 ms/op
                 getUser·p0.999:  14.396 ms/op
                 getUser·p0.9999: 30.798 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241492
  mean =      3.973 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 151 
    [ 2.500,  5.000) = 226574 
    [ 5.000,  7.500) = 11673 
    [ 7.500, 10.000) = 2233 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     22.168 ms/op
     p(99.9900) =     30.371 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.440 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.018 ms/op
Iteration   1: 4.489 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  23.128 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.622 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.080 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 22.259 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.628 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.884 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209562
  mean =      4.579 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 182175 
    [ 5.000,  7.500) = 22485 
    [ 7.500, 10.000) = 3435 
    [10.000, 12.500) = 896 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.833 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     25.560 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.355 ± 3.075  ops/ms
ClientPb.existUser                       thrpt       3   8.512 ± 4.920  ops/ms
ClientPb.getUser                         thrpt       3   8.250 ± 1.056  ops/ms
ClientPb.listUser                        thrpt       3   7.081 ± 2.417  ops/ms
ClientPb.createUser                       avgt       3   3.928 ± 2.129   ms/op
ClientPb.existUser                        avgt       3   3.724 ± 1.013   ms/op
ClientPb.getUser                          avgt       3   3.991 ± 2.512   ms/op
ClientPb.listUser                         avgt       3   4.556 ± 1.745   ms/op
ClientPb.createUser                     sample  243527   3.940 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.468           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.690           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.602           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.717           ms/op
ClientPb.existUser                      sample  252042   3.807 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.184           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.217           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.661           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.637           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  241492   3.973 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.585           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.168           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.371           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  209562   4.579 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.104           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.560           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
