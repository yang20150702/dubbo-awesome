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
# Warmup Iteration   1: 1.521 ops/ms
# Warmup Iteration   2: 3.627 ops/ms
# Warmup Iteration   3: 6.930 ops/ms
Iteration   1: 7.330 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.664 ±(99.9%) 6.902 ops/ms [Average]
  (min, avg, max) = (7.330, 7.664, 8.074), stdev = 0.378
  CI (99.9%): [0.762, 14.565] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 6.659 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 8.448 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.286 ±(99.9%) 2.566 ops/ms [Average]
  (min, avg, max) = (8.197, 8.286, 8.448), stdev = 0.141
  CI (99.9%): [5.720, 10.852] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 7.500 ops/ms
Iteration   1: 7.708 ops/ms
Iteration   2: 7.519 ops/ms
Iteration   3: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.644 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (7.519, 7.644, 7.708), stdev = 0.108
  CI (99.9%): [5.671, 9.617] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.236 ops/ms
# Warmup Iteration   2: 5.631 ops/ms
# Warmup Iteration   3: 6.549 ops/ms
Iteration   1: 6.644 ops/ms
Iteration   2: 6.755 ops/ms
Iteration   3: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.815 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (6.644, 6.815, 7.047), stdev = 0.208
  CI (99.9%): [3.017, 10.613] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.630 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.281 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.005 ms/op
Iteration   1: 4.126 ±(99.9%) 0.009 ms/op
Iteration   2: 4.130 ±(99.9%) 0.005 ms/op
Iteration   3: 4.054 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.103 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (4.054, 4.103, 4.130), stdev = 0.042
  CI (99.9%): [3.329, 4.878] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.713 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.008 ms/op
Iteration   1: 3.960 ±(99.9%) 0.010 ms/op
Iteration   2: 3.869 ±(99.9%) 0.006 ms/op
Iteration   3: 3.892 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.907 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.869, 3.907, 3.960), stdev = 0.047
  CI (99.9%): [3.043, 4.771] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.480 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.005 ms/op
Iteration   1: 4.034 ±(99.9%) 0.007 ms/op
Iteration   2: 3.912 ±(99.9%) 0.007 ms/op
Iteration   3: 4.114 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.020 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (3.912, 4.020, 4.114), stdev = 0.101
  CI (99.9%): [2.169, 5.871] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.726 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.419 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.082 ±(99.9%) 0.010 ms/op
Iteration   1: 4.874 ±(99.9%) 0.010 ms/op
Iteration   2: 4.737 ±(99.9%) 0.011 ms/op
Iteration   3: 4.811 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.807 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (4.737, 4.807, 4.874), stdev = 0.069
  CI (99.9%): [3.557, 6.058] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.894 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.017 ms/op
Iteration   1: 4.082 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 26.449 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 4.051 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.577 ms/op
                 createUser·p0.999:  27.098 ms/op
                 createUser·p0.9999: 32.953 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 4.024 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  12.083 ms/op
                 createUser·p0.9999: 31.361 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236885
  mean =      4.052 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 219223 
    [ 5.000,  7.500) = 15095 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     21.536 ms/op
     p(99.9900) =     32.123 ms/op
     p(99.9990) =     33.247 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.520 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 25.003 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.981 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   8.405 ms/op
                 existUser·p0.999:  24.314 ms/op
                 existUser·p0.9999: 27.606 ms/op
                 existUser·p1.00:   31.195 ms/op

Iteration   3: 3.943 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.759 ms/op
                 existUser·p0.999:  15.658 ms/op
                 existUser·p0.9999: 28.013 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242698
  mean =      3.956 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210 
    [ 2.500,  5.000) = 228707 
    [ 5.000,  7.500) = 11085 
    [ 7.500, 10.000) = 1604 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     15.694 ms/op
     p(99.9900) =     27.844 ms/op
     p(99.9990) =     30.308 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.801 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.977 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.017 ms/op
Iteration   1: 4.119 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  22.925 ms/op
                 getUser·p0.9999: 26.514 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 4.041 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  20.111 ms/op
                 getUser·p0.9999: 33.828 ms/op
                 getUser·p1.00:   35.062 ms/op

Iteration   3: 4.089 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  14.887 ms/op
                 getUser·p0.9999: 28.612 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234990
  mean =      4.083 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 219195 
    [ 5.000,  7.500) = 10886 
    [ 7.500, 10.000) = 3740 
    [10.000, 12.500) = 711 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.939 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     32.260 ms/op
     p(99.9990) =     34.842 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.645 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.021 ms/op
Iteration   1: 4.913 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  25.721 ms/op
                 listUser·p0.9999: 33.914 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 4.898 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 21.575 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.836 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  18.089 ms/op
                 listUser·p0.9999: 22.655 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196437
  mean =      4.882 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 153999 
    [ 5.000,  7.500) = 34179 
    [ 7.500, 10.000) = 6386 
    [10.000, 12.500) = 1094 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      7.030 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     31.854 ms/op
     p(99.9990) =     34.608 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.664 ± 6.902  ops/ms
ClientPb.existUser                       thrpt       3   8.286 ± 2.566  ops/ms
ClientPb.getUser                         thrpt       3   7.644 ± 1.973  ops/ms
ClientPb.listUser                        thrpt       3   6.815 ± 3.798  ops/ms
ClientPb.createUser                       avgt       3   4.103 ± 0.775   ms/op
ClientPb.existUser                        avgt       3   3.907 ± 0.864   ms/op
ClientPb.getUser                          avgt       3   4.020 ± 1.851   ms/op
ClientPb.listUser                         avgt       3   4.807 ± 1.251   ms/op
ClientPb.createUser                     sample  236885   4.052 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.471           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.536           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.123           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  242698   3.956 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.992           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.694           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.195           ms/op
ClientPb.getUser                        sample  234990   4.083 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.602           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.260           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.062           ms/op
ClientPb.listUser                       sample  196437   4.882 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.145           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.854           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
