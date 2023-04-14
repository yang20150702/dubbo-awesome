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
# Warmup Iteration   1: 1.162 ops/ms
# Warmup Iteration   2: 2.786 ops/ms
# Warmup Iteration   3: 5.755 ops/ms
Iteration   1: 5.979 ops/ms
Iteration   2: 6.523 ops/ms
Iteration   3: 6.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.198 ±(99.9%) 5.245 ops/ms [Average]
  (min, avg, max) = (5.979, 6.198, 6.523), stdev = 0.287
  CI (99.9%): [0.953, 11.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 5.357 ops/ms
# Warmup Iteration   3: 6.514 ops/ms
Iteration   1: 6.643 ops/ms
Iteration   2: 6.295 ops/ms
Iteration   3: 6.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.572 ±(99.9%) 4.547 ops/ms [Average]
  (min, avg, max) = (6.295, 6.572, 6.778), stdev = 0.249
  CI (99.9%): [2.025, 11.119] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 5.226 ops/ms
# Warmup Iteration   3: 6.225 ops/ms
Iteration   1: 6.094 ops/ms
Iteration   2: 6.336 ops/ms
Iteration   3: 6.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.200 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (6.094, 6.200, 6.336), stdev = 0.124
  CI (99.9%): [3.938, 8.462] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.440 ops/ms
# Warmup Iteration   2: 4.295 ops/ms
# Warmup Iteration   3: 5.412 ops/ms
Iteration   1: 5.297 ops/ms
Iteration   2: 5.533 ops/ms
Iteration   3: 5.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.448 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (5.297, 5.448, 5.533), stdev = 0.131
  CI (99.9%): [3.056, 7.839] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.851 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 6.497 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.014 ms/op
Iteration   1: 5.410 ±(99.9%) 0.007 ms/op
Iteration   2: 5.068 ±(99.9%) 0.023 ms/op
Iteration   3: 5.017 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.165 ±(99.9%) 3.901 ms/op [Average]
  (min, avg, max) = (5.017, 5.165, 5.410), stdev = 0.214
  CI (99.9%): [1.264, 9.065] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.840 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.052 ±(99.9%) 0.009 ms/op
Iteration   1: 4.787 ±(99.9%) 0.014 ms/op
Iteration   2: 5.230 ±(99.9%) 0.011 ms/op
Iteration   3: 4.995 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.004 ±(99.9%) 4.046 ms/op [Average]
  (min, avg, max) = (4.787, 5.004, 5.230), stdev = 0.222
  CI (99.9%): [0.957, 9.050] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.947 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.181 ±(99.9%) 0.011 ms/op
Iteration   1: 5.297 ±(99.9%) 0.013 ms/op
Iteration   2: 4.996 ±(99.9%) 0.015 ms/op
Iteration   3: 5.094 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.129 ±(99.9%) 2.794 ms/op [Average]
  (min, avg, max) = (4.996, 5.129, 5.297), stdev = 0.153
  CI (99.9%): [2.335, 7.923] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 22.609 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.100 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.771 ±(99.9%) 0.016 ms/op
Iteration   1: 5.948 ±(99.9%) 0.013 ms/op
Iteration   2: 5.881 ±(99.9%) 0.022 ms/op
Iteration   3: 5.699 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.843 ±(99.9%) 2.358 ms/op [Average]
  (min, avg, max) = (5.699, 5.843, 5.948), stdev = 0.129
  CI (99.9%): [3.485, 8.201] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.460 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.158 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.588 ±(99.9%) 0.025 ms/op
Iteration   1: 5.434 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.774 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  22.128 ms/op
                 createUser·p0.9999: 31.068 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   2: 5.159 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.136 ms/op
                 createUser·p0.95:   7.102 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  23.669 ms/op
                 createUser·p0.9999: 27.446 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 5.211 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   7.324 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  27.056 ms/op
                 createUser·p0.9999: 29.913 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182267
  mean =      5.266 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 95983 
    [ 5.000,  7.500) = 77280 
    [ 7.500, 10.000) = 6445 
    [10.000, 12.500) = 1669 
    [12.500, 15.000) = 502 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     23.117 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     31.770 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 16.895 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.997 ±(99.9%) 0.017 ms/op
Iteration   1: 4.935 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   7.004 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  18.066 ms/op
                 existUser·p0.9999: 24.677 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 4.797 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.042 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.210 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  15.434 ms/op
                 existUser·p0.9999: 29.908 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 4.998 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  24.544 ms/op
                 existUser·p0.9999: 26.922 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195380
  mean =      4.909 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 140213 
    [ 5.000,  7.500) = 49428 
    [ 7.500, 10.000) = 4092 
    [10.000, 12.500) = 929 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     27.016 ms/op
     p(99.9990) =     30.686 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 17.458 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.187 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.396 ±(99.9%) 0.021 ms/op
Iteration   1: 5.156 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.404 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.922 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  21.591 ms/op
                 getUser·p0.9999: 24.242 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   2: 5.380 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   12.763 ms/op
                 getUser·p0.999:  27.567 ms/op
                 getUser·p0.9999: 31.164 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 5.089 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   9.273 ms/op
                 getUser·p0.999:  23.958 ms/op
                 getUser·p0.9999: 28.106 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184309
  mean =      5.205 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 105040 
    [ 5.000,  7.500) = 70708 
    [ 7.500, 10.000) = 5717 
    [10.000, 12.500) = 1773 
    [12.500, 15.000) = 544 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     30.694 ms/op
     p(99.9990) =     31.571 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 19.317 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 6.651 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.803 ±(99.9%) 0.022 ms/op
Iteration   1: 5.695 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  25.189 ms/op
                 listUser·p0.9999: 28.226 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 5.602 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  25.915 ms/op
                 listUser·p0.9999: 32.423 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   3: 5.681 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 23.236 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 169506
  mean =      5.659 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 27300 
    [ 5.000,  7.500) = 134405 
    [ 7.500, 10.000) = 5679 
    [10.000, 12.500) = 1434 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.370 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     31.328 ms/op
     p(99.9990) =     33.723 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.198 ± 5.245  ops/ms
ClientPb.existUser                       thrpt       3   6.572 ± 4.547  ops/ms
ClientPb.getUser                         thrpt       3   6.200 ± 2.262  ops/ms
ClientPb.listUser                        thrpt       3   5.448 ± 2.392  ops/ms
ClientPb.createUser                       avgt       3   5.165 ± 3.901   ms/op
ClientPb.existUser                        avgt       3   5.004 ± 4.046   ms/op
ClientPb.getUser                          avgt       3   5.129 ± 2.794   ms/op
ClientPb.listUser                         avgt       3   5.843 ± 2.358   ms/op
ClientPb.createUser                     sample  182267   5.266 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.309           ms/op
ClientPb.existUser                      sample  195380   4.909 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.712           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.856           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.016           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  184309   5.205 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.961           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.626           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.694           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  169506   5.659 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.519           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.390           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.370           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.150           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.328           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.406           ms/op
