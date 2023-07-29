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
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 3.400 ops/ms
# Warmup Iteration   3: 7.465 ops/ms
Iteration   1: 7.280 ops/ms
Iteration   2: 7.982 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.794 ±(99.9%) 8.212 ops/ms [Average]
  (min, avg, max) = (7.280, 7.794, 8.120), stdev = 0.450
  CI (99.9%): [≈ 0, 16.007] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.291 ops/ms
# Warmup Iteration   2: 6.523 ops/ms
# Warmup Iteration   3: 8.200 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.198 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (8.022, 8.198, 8.308), stdev = 0.154
  CI (99.9%): [5.384, 11.012] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 7.075 ops/ms
# Warmup Iteration   3: 7.571 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 8.041 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.914 ±(99.9%) 2.415 ops/ms [Average]
  (min, avg, max) = (7.777, 7.914, 8.041), stdev = 0.132
  CI (99.9%): [5.499, 10.329] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 5.773 ops/ms
# Warmup Iteration   3: 6.774 ops/ms
Iteration   1: 6.766 ops/ms
Iteration   2: 7.161 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.910 ±(99.9%) 3.979 ops/ms [Average]
  (min, avg, max) = (6.766, 6.910, 7.161), stdev = 0.218
  CI (99.9%): [2.932, 10.889] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.061 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.011 ms/op
Iteration   1: 3.986 ±(99.9%) 0.008 ms/op
Iteration   2: 3.960 ±(99.9%) 0.006 ms/op
Iteration   3: 3.960 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.969 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.960, 3.969, 3.986), stdev = 0.015
  CI (99.9%): [3.695, 4.243] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.770 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.005 ms/op
Iteration   1: 3.644 ±(99.9%) 0.009 ms/op
Iteration   2: 3.635 ±(99.9%) 0.013 ms/op
Iteration   3: 3.896 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.725 ±(99.9%) 2.702 ms/op [Average]
  (min, avg, max) = (3.635, 3.725, 3.896), stdev = 0.148
  CI (99.9%): [1.023, 6.427] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.063 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.009 ms/op
Iteration   1: 4.179 ±(99.9%) 0.004 ms/op
Iteration   2: 4.080 ±(99.9%) 0.009 ms/op
Iteration   3: 3.828 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.029 ±(99.9%) 3.301 ms/op [Average]
  (min, avg, max) = (3.828, 4.029, 4.179), stdev = 0.181
  CI (99.9%): [0.728, 7.330] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.312 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.739 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.959 ±(99.9%) 0.010 ms/op
Iteration   1: 4.739 ±(99.9%) 0.017 ms/op
Iteration   2: 4.566 ±(99.9%) 0.018 ms/op
Iteration   3: 4.504 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.603 ±(99.9%) 2.229 ms/op [Average]
  (min, avg, max) = (4.504, 4.603, 4.739), stdev = 0.122
  CI (99.9%): [2.374, 6.832] (assumes normal distribution)


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
# Warmup Iteration   1: 12.853 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.017 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 44.639 ms/op
                 createUser·p1.00:   44.958 ms/op

Iteration   2: 4.032 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  25.250 ms/op
                 createUser·p0.9999: 34.406 ms/op
                 createUser·p1.00:   38.470 ms/op

Iteration   3: 4.097 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  28.600 ms/op
                 createUser·p0.9999: 47.079 ms/op
                 createUser·p1.00:   48.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236178
  mean =      4.062 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 218299 
    [ 5.000, 10.000) = 17107 
    [10.000, 15.000) = 454 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     24.242 ms/op
     p(99.9900) =     44.852 ms/op
     p(99.9990) =     47.728 ms/op
     p(99.9999) =     48.103 ms/op
    p(100.0000) =     48.103 ms/op


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
# Warmup Iteration   1: 12.117 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.013 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.900 ms/op
                 existUser·p0.999:  10.293 ms/op
                 existUser·p0.9999: 24.907 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 3.946 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.894 ms/op
                 existUser·p0.999:  27.361 ms/op
                 existUser·p0.9999: 38.594 ms/op
                 existUser·p1.00:   39.649 ms/op

Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 31.384 ms/op
                 existUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243285
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 230946 
    [ 5.000,  7.500) = 10089 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.218 ms/op
     p(99.9000) =     15.839 ms/op
     p(99.9900) =     36.111 ms/op
     p(99.9990) =     38.928 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 13.309 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.844 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.013 ms/op
Iteration   1: 4.056 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  23.331 ms/op
                 getUser·p0.9999: 30.842 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 3.880 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  23.888 ms/op
                 getUser·p0.9999: 26.829 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.992 ms/op
                 getUser·p0.999:  11.428 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244302
  mean =      3.931 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 233358 
    [ 5.000,  7.500) = 8326 
    [ 7.500, 10.000) = 1690 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     22.895 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     31.133 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 13.381 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.661 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.913 ±(99.9%) 0.017 ms/op
Iteration   1: 4.804 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  23.442 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 4.733 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 20.062 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.709 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.469 ms/op
                 listUser·p0.9999: 22.415 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202062
  mean =      4.748 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 167048 
    [ 5.000,  7.500) = 29315 
    [ 7.500, 10.000) = 4402 
    [10.000, 12.500) = 691 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     26.089 ms/op
     p(99.9990) =     28.686 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.794 ± 8.212  ops/ms
ClientPb.existUser                       thrpt       3   8.198 ± 2.814  ops/ms
ClientPb.getUser                         thrpt       3   7.914 ± 2.415  ops/ms
ClientPb.listUser                        thrpt       3   6.910 ± 3.979  ops/ms
ClientPb.createUser                       avgt       3   3.969 ± 0.274   ms/op
ClientPb.existUser                        avgt       3   3.725 ± 2.702   ms/op
ClientPb.getUser                          avgt       3   4.029 ± 3.301   ms/op
ClientPb.listUser                         avgt       3   4.603 ± 2.229   ms/op
ClientPb.createUser                     sample  236178   4.062 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.642           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.307           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.852           ms/op
ClientPb.createUser:createUser·p1.00    sample          48.103           ms/op
ClientPb.existUser                      sample  243285   3.943 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.776           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.111           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.649           ms/op
ClientPb.getUser                        sample  244302   3.931 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.895           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.457           ms/op
ClientPb.listUser                       sample  202062   4.748 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.191           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.645           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.089           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
