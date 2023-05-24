# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.596 ops/ms
# Warmup Iteration   3: 8.651 ops/ms
Iteration   1: 9.635 ops/ms
Iteration   2: 9.565 ops/ms
Iteration   3: 9.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.672 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (9.565, 9.672, 9.817), stdev = 0.130
  CI (99.9%): [7.302, 12.042] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 9.242 ops/ms
# Warmup Iteration   3: 9.821 ops/ms
Iteration   1: 10.034 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.992 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (9.927, 9.992, 10.034), stdev = 0.057
  CI (99.9%): [8.945, 11.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.200 ops/ms
# Warmup Iteration   2: 8.767 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 9.674 ops/ms
Iteration   2: 9.987 ops/ms
Iteration   3: 9.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.858 ±(99.9%) 2.976 ops/ms [Average]
  (min, avg, max) = (9.674, 9.858, 9.987), stdev = 0.163
  CI (99.9%): [6.882, 12.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 7.894 ops/ms
# Warmup Iteration   3: 8.450 ops/ms
Iteration   1: 8.439 ops/ms
Iteration   2: 8.653 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.523 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (8.439, 8.523, 8.653), stdev = 0.115
  CI (99.9%): [6.434, 10.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.060 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.002 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.255 ±(99.9%) 0.006 ms/op
Iteration   3: 3.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.184 ±(99.9%) 1.641 ms/op [Average]
  (min, avg, max) = (3.083, 3.184, 3.255), stdev = 0.090
  CI (99.9%): [1.543, 4.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.203 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.005 ms/op
Iteration   2: 3.117 ±(99.9%) 0.005 ms/op
Iteration   3: 3.265 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.172 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.117, 3.172, 3.265), stdev = 0.081
  CI (99.9%): [1.702, 4.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.463 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.005 ms/op
Iteration   1: 3.409 ±(99.9%) 0.005 ms/op
Iteration   2: 3.357 ±(99.9%) 0.006 ms/op
Iteration   3: 3.277 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.347 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.277, 3.347, 3.409), stdev = 0.066
  CI (99.9%): [2.135, 4.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.301 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.006 ms/op
Iteration   1: 3.755 ±(99.9%) 0.004 ms/op
Iteration   2: 3.757 ±(99.9%) 0.009 ms/op
Iteration   3: 3.800 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.755, 3.771, 3.800), stdev = 0.026
  CI (99.9%): [3.301, 4.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.044 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.010 ms/op
Iteration   1: 3.263 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  12.680 ms/op
                 createUser·p0.9999: 40.383 ms/op
                 createUser·p1.00:   44.630 ms/op

Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  19.974 ms/op
                 createUser·p0.9999: 24.379 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  14.980 ms/op
                 createUser·p0.9999: 30.063 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291776
  mean =      3.288 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 284823 
    [ 5.000, 10.000) = 6585 
    [10.000, 15.000) = 79 
    [15.000, 20.000) = 74 
    [20.000, 25.000) = 151 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     14.842 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     43.739 ms/op
     p(99.9999) =     44.630 ms/op
    p(100.0000) =     44.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.253 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 20.911 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  17.747 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  12.613 ms/op
                 existUser·p0.9999: 29.721 ms/op
                 existUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299806
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12933 
    [ 2.500,  5.000) = 280864 
    [ 5.000,  7.500) = 5068 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     28.444 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.044 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  10.761 ms/op
                 getUser·p0.9999: 24.221 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.227 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292502
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17496 
    [ 2.500,  5.000) = 268071 
    [ 5.000,  7.500) = 6130 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     23.544 ms/op
     p(99.9990) =     24.525 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.904 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  19.649 ms/op
                 listUser·p0.9999: 22.450 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 3.810 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.846 ms/op
                 listUser·p0.9999: 15.806 ms/op
                 listUser·p1.00:   16.482 ms/op

Iteration   3: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.263 ms/op
                 listUser·p0.999:  14.269 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251827
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 244464 
    [ 5.000,  7.500) = 5398 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     22.369 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.672 ± 2.370  ops/ms
ClientPb.existUser                       thrpt       3   9.992 ± 1.048  ops/ms
ClientPb.getUser                         thrpt       3   9.858 ± 2.976  ops/ms
ClientPb.listUser                        thrpt       3   8.523 ± 2.089  ops/ms
ClientPb.createUser                       avgt       3   3.184 ± 1.641   ms/op
ClientPb.existUser                        avgt       3   3.172 ± 1.471   ms/op
ClientPb.getUser                          avgt       3   3.347 ± 1.212   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 0.470   ms/op
ClientPb.createUser                     sample  291776   3.288 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.842           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.339           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.630           ms/op
ClientPb.existUser                      sample  299806   3.200 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.097           ms/op
ClientPb.getUser                        sample  292502   3.282 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.531           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  251827   3.811 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.090           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.369           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.757           ms/op
