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
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 4.028 ops/ms
# Warmup Iteration   3: 7.244 ops/ms
Iteration   1: 7.536 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 7.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.773 ±(99.9%) 3.877 ops/ms [Average]
  (min, avg, max) = (7.536, 7.773, 7.947), stdev = 0.213
  CI (99.9%): [3.897, 11.650] (assumes normal distribution)


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
# Warmup Iteration   1: 2.433 ops/ms
# Warmup Iteration   2: 6.984 ops/ms
# Warmup Iteration   3: 7.970 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.247 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (8.038, 8.247, 8.398), stdev = 0.187
  CI (99.9%): [4.843, 11.650] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.453 ops/ms
# Warmup Iteration   2: 6.287 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 7.836 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.023 ±(99.9%) 4.738 ops/ms [Average]
  (min, avg, max) = (7.836, 8.023, 8.320), stdev = 0.260
  CI (99.9%): [3.286, 12.761] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 5.812 ops/ms
# Warmup Iteration   3: 6.754 ops/ms
Iteration   1: 6.623 ops/ms
Iteration   2: 6.617 ops/ms
Iteration   3: 6.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.740 ±(99.9%) 3.794 ops/ms [Average]
  (min, avg, max) = (6.617, 6.740, 6.980), stdev = 0.208
  CI (99.9%): [2.947, 10.534] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.334 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
Iteration   2: 3.904 ±(99.9%) 0.013 ms/op
Iteration   3: 3.984 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.955 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.904, 3.955, 3.984), stdev = 0.044
  CI (99.9%): [3.147, 4.764] (assumes normal distribution)


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
# Warmup Iteration   1: 12.487 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.008 ms/op
Iteration   1: 3.701 ±(99.9%) 0.008 ms/op
Iteration   2: 3.749 ±(99.9%) 0.004 ms/op
Iteration   3: 3.735 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.728 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.701, 3.728, 3.749), stdev = 0.025
  CI (99.9%): [3.275, 4.182] (assumes normal distribution)


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
# Warmup Iteration   1: 13.258 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.006 ms/op
Iteration   1: 3.919 ±(99.9%) 0.003 ms/op
Iteration   2: 4.073 ±(99.9%) 0.009 ms/op
Iteration   3: 3.896 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.962 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.896, 3.962, 4.073), stdev = 0.096
  CI (99.9%): [2.207, 5.717] (assumes normal distribution)


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
# Warmup Iteration   1: 13.981 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.946 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.010 ms/op
Iteration   1: 4.746 ±(99.9%) 0.012 ms/op
Iteration   2: 4.776 ±(99.9%) 0.014 ms/op
Iteration   3: 4.669 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.730 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (4.669, 4.730, 4.776), stdev = 0.055
  CI (99.9%): [3.731, 5.730] (assumes normal distribution)


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
# Warmup Iteration   1: 12.302 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.019 ms/op
Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  23.402 ms/op
                 createUser·p0.9999: 25.661 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  24.042 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.023 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 28.407 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239963
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 229278 
    [ 5.000,  7.500) = 8617 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 159 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     23.299 ms/op
     p(99.9900) =     29.361 ms/op
     p(99.9990) =     31.444 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 13.114 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.013 ms/op
Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.896 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.090 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 26.035 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.839 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  23.377 ms/op
                 existUser·p0.9999: 29.087 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   3: 3.967 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.999 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  12.802 ms/op
                 existUser·p0.9999: 31.195 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248681
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 240 
    [ 2.500,  5.000) = 240796 
    [ 5.000,  7.500) = 5656 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     29.657 ms/op
     p(99.9990) =     32.098 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 12.829 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.012 ms/op
Iteration   1: 4.129 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.997 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  23.810 ms/op
                 getUser·p0.9999: 26.280 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 4.073 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.450 ms/op
                 getUser·p0.999:  11.253 ms/op
                 getUser·p0.9999: 27.843 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  27.604 ms/op
                 getUser·p0.9999: 32.693 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234886
  mean =      4.089 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 221312 
    [ 5.000,  7.500) = 9668 
    [ 7.500, 10.000) = 3004 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     23.899 ms/op
     p(99.9900) =     31.950 ms/op
     p(99.9990) =     33.314 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 15.745 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.612 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.018 ms/op
Iteration   1: 4.738 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  25.018 ms/op
                 listUser·p0.9999: 27.246 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 4.736 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 4.707 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203015
  mean =      4.727 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 173593 
    [ 5.000,  7.500) = 23566 
    [ 7.500, 10.000) = 4539 
    [10.000, 12.500) = 654 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.721 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.773 ± 3.877  ops/ms
ClientPb.existUser                       thrpt       3   8.247 ± 3.404  ops/ms
ClientPb.getUser                         thrpt       3   8.023 ± 4.738  ops/ms
ClientPb.listUser                        thrpt       3   6.740 ± 3.794  ops/ms
ClientPb.createUser                       avgt       3   3.955 ± 0.808   ms/op
ClientPb.existUser                        avgt       3   3.728 ± 0.453   ms/op
ClientPb.getUser                          avgt       3   3.962 ± 1.755   ms/op
ClientPb.listUser                         avgt       3   4.730 ± 0.999   ms/op
ClientPb.createUser                     sample  239963   3.999 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.503           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.361           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  248681   3.858 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.004           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.657           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  234886   4.089 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.632           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.899           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.950           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  203015   4.727 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.054           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.803           ms/op
