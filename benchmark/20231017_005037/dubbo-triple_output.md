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
# Warmup Iteration   1: 1.098 ops/ms
# Warmup Iteration   2: 2.395 ops/ms
# Warmup Iteration   3: 5.703 ops/ms
Iteration   1: 5.463 ops/ms
Iteration   2: 5.653 ops/ms
Iteration   3: 5.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.695 ±(99.9%) 4.657 ops/ms [Average]
  (min, avg, max) = (5.463, 5.695, 5.969), stdev = 0.255
  CI (99.9%): [1.038, 10.352] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 5.470 ops/ms
# Warmup Iteration   3: 6.419 ops/ms
Iteration   1: 6.400 ops/ms
Iteration   2: 6.521 ops/ms
Iteration   3: 6.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.386 ±(99.9%) 2.590 ops/ms [Average]
  (min, avg, max) = (6.238, 6.386, 6.521), stdev = 0.142
  CI (99.9%): [3.797, 8.976] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.588 ops/ms
# Warmup Iteration   3: 5.852 ops/ms
Iteration   1: 6.175 ops/ms
Iteration   2: 6.057 ops/ms
Iteration   3: 5.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.072 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (5.984, 6.072, 6.175), stdev = 0.096
  CI (99.9%): [4.315, 7.829] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 5.008 ops/ms
Iteration   1: 5.157 ops/ms
Iteration   2: 5.185 ops/ms
Iteration   3: 5.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.193 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (5.157, 5.193, 5.237), stdev = 0.041
  CI (99.9%): [4.451, 5.934] (assumes normal distribution)


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
# Warmup Iteration   1: 18.658 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.010 ms/op
Iteration   1: 5.419 ±(99.9%) 0.009 ms/op
Iteration   2: 5.184 ±(99.9%) 0.015 ms/op
Iteration   3: 5.440 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.348 ±(99.9%) 2.592 ms/op [Average]
  (min, avg, max) = (5.184, 5.348, 5.440), stdev = 0.142
  CI (99.9%): [2.756, 7.939] (assumes normal distribution)


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
# Warmup Iteration   1: 16.080 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.969 ±(99.9%) 0.008 ms/op
Iteration   2: 5.189 ±(99.9%) 0.008 ms/op
Iteration   3: 4.860 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.006 ±(99.9%) 3.061 ms/op [Average]
  (min, avg, max) = (4.860, 5.006, 5.189), stdev = 0.168
  CI (99.9%): [1.945, 8.067] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.539 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.922 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.014 ms/op
Iteration   1: 5.443 ±(99.9%) 0.009 ms/op
Iteration   2: 5.480 ±(99.9%) 0.016 ms/op
Iteration   3: 5.238 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.387 ±(99.9%) 2.375 ms/op [Average]
  (min, avg, max) = (5.238, 5.387, 5.480), stdev = 0.130
  CI (99.9%): [3.012, 7.762] (assumes normal distribution)


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
# Warmup Iteration   1: 17.605 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.980 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.406 ±(99.9%) 0.008 ms/op
Iteration   1: 6.319 ±(99.9%) 0.014 ms/op
Iteration   2: 6.246 ±(99.9%) 0.009 ms/op
Iteration   3: 6.294 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.286 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (6.246, 6.286, 6.319), stdev = 0.037
  CI (99.9%): [5.613, 6.960] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.711 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 6.970 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.867 ±(99.9%) 0.028 ms/op
Iteration   1: 5.311 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   10.992 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 31.876 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   2: 5.480 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  26.695 ms/op
                 createUser·p0.9999: 31.097 ms/op
                 createUser·p1.00:   42.598 ms/op

Iteration   3: 5.348 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   7.733 ms/op
                 createUser·p0.99:   10.830 ms/op
                 createUser·p0.999:  32.445 ms/op
                 createUser·p0.9999: 41.289 ms/op
                 createUser·p1.00:   41.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178391
  mean =      5.379 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 85431 
    [ 5.000, 10.000) = 90401 
    [10.000, 15.000) = 1990 
    [15.000, 20.000) = 238 
    [20.000, 25.000) = 98 
    [25.000, 30.000) = 93 
    [30.000, 35.000) = 115 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     28.233 ms/op
     p(99.9900) =     39.091 ms/op
     p(99.9990) =     41.931 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.441 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.098 ±(99.9%) 0.020 ms/op
Iteration   1: 5.468 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   7.258 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   11.944 ms/op
                 existUser·p0.999:  21.150 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 5.233 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.711 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   11.420 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 26.671 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 5.040 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  31.215 ms/op
                 existUser·p0.9999: 39.059 ms/op
                 existUser·p1.00:   48.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183128
  mean =      5.241 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 108561 
    [ 5.000, 10.000) = 71568 
    [10.000, 15.000) = 2446 
    [15.000, 20.000) = 258 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 82 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     38.580 ms/op
     p(99.9990) =     41.239 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.351 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.187 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.533 ±(99.9%) 0.023 ms/op
Iteration   1: 5.406 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   12.911 ms/op
                 getUser·p0.999:  25.127 ms/op
                 getUser·p0.9999: 32.574 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   2: 5.633 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   7.971 ms/op
                 getUser·p0.95:   9.257 ms/op
                 getUser·p0.99:   12.812 ms/op
                 getUser·p0.999:  24.117 ms/op
                 getUser·p0.9999: 29.631 ms/op
                 getUser·p1.00:   32.637 ms/op

Iteration   3: 5.343 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.636 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  19.164 ms/op
                 getUser·p0.9999: 28.744 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175847
  mean =      5.458 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 84018 
    [ 5.000,  7.500) = 77947 
    [ 7.500, 10.000) = 9740 
    [10.000, 12.500) = 2638 
    [12.500, 15.000) = 681 
    [15.000, 17.500) = 359 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     32.678 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 20.199 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 8.507 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.413 ±(99.9%) 0.027 ms/op
Iteration   1: 6.330 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  31.092 ms/op
                 listUser·p0.9999: 46.658 ms/op
                 listUser·p1.00:   49.611 ms/op

Iteration   2: 6.064 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  28.541 ms/op
                 listUser·p0.9999: 33.093 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   3: 6.128 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   12.632 ms/op
                 listUser·p0.999:  23.298 ms/op
                 listUser·p0.9999: 27.733 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155425
  mean =      6.172 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12034 
    [ 5.000, 10.000) = 138554 
    [10.000, 15.000) = 4010 
    [15.000, 20.000) = 385 
    [20.000, 25.000) = 203 
    [25.000, 30.000) = 148 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      5.808 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     27.989 ms/op
     p(99.9900) =     43.218 ms/op
     p(99.9990) =     48.376 ms/op
     p(99.9999) =     49.611 ms/op
    p(100.0000) =     49.611 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.695 ± 4.657  ops/ms
ClientPb.existUser                       thrpt       3   6.386 ± 2.590  ops/ms
ClientPb.getUser                         thrpt       3   6.072 ± 1.757  ops/ms
ClientPb.listUser                        thrpt       3   5.193 ± 0.742  ops/ms
ClientPb.createUser                       avgt       3   5.348 ± 2.592   ms/op
ClientPb.existUser                        avgt       3   5.006 ± 3.061   ms/op
ClientPb.getUser                          avgt       3   5.387 ± 2.375   ms/op
ClientPb.listUser                         avgt       3   6.286 ± 0.674   ms/op
ClientPb.createUser                     sample  178391   5.379 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.774           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.598           ms/op
ClientPb.existUser                      sample  183128   5.241 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.922           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.370           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.412           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.580           ms/op
ClientPb.existUser:existUser·p1.00      sample          48.103           ms/op
ClientPb.getUser                        sample  175847   5.458 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.616           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.993           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.134           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.752           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  155425   6.172 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.989           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.218           ms/op
ClientPb.listUser:listUser·p1.00        sample          49.611           ms/op
