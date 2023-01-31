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
# Warmup Iteration   1: 1.703 ops/ms
# Warmup Iteration   2: 3.901 ops/ms
# Warmup Iteration   3: 7.316 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 8.216 ops/ms
Iteration   3: 8.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.043 ±(99.9%) 5.819 ops/ms [Average]
  (min, avg, max) = (7.675, 8.043, 8.238), stdev = 0.319
  CI (99.9%): [2.224, 13.862] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.440 ops/ms
# Warmup Iteration   3: 8.643 ops/ms
Iteration   1: 8.686 ops/ms
Iteration   2: 8.452 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.621 ±(99.9%) 2.696 ops/ms [Average]
  (min, avg, max) = (8.452, 8.621, 8.725), stdev = 0.148
  CI (99.9%): [5.925, 11.317] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.967 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.083 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (7.972, 8.083, 8.160), stdev = 0.099
  CI (99.9%): [6.285, 9.881] (assumes normal distribution)


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
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 5.606 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 6.822 ops/ms
Iteration   2: 7.153 ops/ms
Iteration   3: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.908 ±(99.9%) 3.931 ops/ms [Average]
  (min, avg, max) = (6.749, 6.908, 7.153), stdev = 0.215
  CI (99.9%): [2.977, 10.839] (assumes normal distribution)


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
# Warmup Iteration   1: 13.073 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.005 ms/op
Iteration   1: 3.955 ±(99.9%) 0.009 ms/op
Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
Iteration   3: 3.937 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.934 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.909, 3.934, 3.955), stdev = 0.023
  CI (99.9%): [3.517, 4.351] (assumes normal distribution)


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
# Warmup Iteration   1: 12.373 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.008 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
Iteration   2: 3.735 ±(99.9%) 0.011 ms/op
Iteration   3: 3.777 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.803 ±(99.9%) 1.530 ms/op [Average]
  (min, avg, max) = (3.735, 3.803, 3.897), stdev = 0.084
  CI (99.9%): [2.273, 5.333] (assumes normal distribution)


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
# Warmup Iteration   1: 12.285 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.004 ms/op
Iteration   1: 4.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
Iteration   3: 3.935 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.971 ±(99.9%) 3.221 ms/op [Average]
  (min, avg, max) = (3.816, 3.971, 4.163), stdev = 0.177
  CI (99.9%): [0.751, 7.192] (assumes normal distribution)


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
# Warmup Iteration   1: 13.545 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.845 ±(99.9%) 0.011 ms/op
Iteration   1: 4.832 ±(99.9%) 0.005 ms/op
Iteration   2: 4.384 ±(99.9%) 0.016 ms/op
Iteration   3: 4.651 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.622 ±(99.9%) 4.111 ms/op [Average]
  (min, avg, max) = (4.384, 4.622, 4.832), stdev = 0.225
  CI (99.9%): [0.511, 8.734] (assumes normal distribution)


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
# Warmup Iteration   1: 11.458 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.019 ms/op
Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.062 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  12.099 ms/op
                 createUser·p0.9999: 25.647 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   2: 4.038 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  25.843 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   3: 3.887 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  25.254 ms/op
                 createUser·p0.9999: 37.487 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243097
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 232878 
    [ 5.000,  7.500) = 7752 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     24.245 ms/op
     p(99.9900) =     36.549 ms/op
     p(99.9990) =     37.852 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.310 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
Iteration   1: 3.775 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  22.430 ms/op
                 existUser·p0.9999: 28.574 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.392 ms/op
                 existUser·p0.999:  10.128 ms/op
                 existUser·p0.9999: 27.670 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   3: 3.857 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  26.352 ms/op
                 existUser·p0.9999: 28.776 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252804
  mean =      3.793 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 499 
    [ 2.500,  5.000) = 245633 
    [ 5.000,  7.500) = 5242 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     21.258 ms/op
     p(99.9900) =     28.457 ms/op
     p(99.9990) =     29.551 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 13.157 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.642 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.015 ms/op
Iteration   1: 4.040 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.555 ms/op
                 getUser·p0.999:  20.659 ms/op
                 getUser·p0.9999: 24.415 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   7.259 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   7.215 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237585
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 226377 
    [ 5.000,  7.500) = 8897 
    [ 7.500, 10.000) = 1669 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     20.821 ms/op
     p(99.9900) =     25.837 ms/op
     p(99.9990) =     28.254 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 13.228 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.430 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.015 ms/op
Iteration   1: 4.851 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  24.859 ms/op
                 listUser·p0.9999: 33.208 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   2: 4.732 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.921 ms/op
                 listUser·p0.9999: 24.035 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 4.822 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 22.196 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199862
  mean =      4.801 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 153980 
    [ 5.000,  7.500) = 40751 
    [ 7.500, 10.000) = 4043 
    [10.000, 12.500) = 531 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     32.309 ms/op
     p(99.9990) =     33.391 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.043 ± 5.819  ops/ms
ClientPb.existUser                       thrpt       3   8.621 ± 2.696  ops/ms
ClientPb.getUser                         thrpt       3   8.083 ± 1.798  ops/ms
ClientPb.listUser                        thrpt       3   6.908 ± 3.931  ops/ms
ClientPb.createUser                       avgt       3   3.934 ± 0.417   ms/op
ClientPb.existUser                        avgt       3   3.803 ± 1.530   ms/op
ClientPb.getUser                          avgt       3   3.971 ± 3.221   ms/op
ClientPb.listUser                         avgt       3   4.622 ± 4.111   ms/op
ClientPb.createUser                     sample  243097   3.946 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.340           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.245           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.549           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.011           ms/op
ClientPb.existUser                      sample  252804   3.793 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.258           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  237585   4.039 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.774           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.381           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.821           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.837           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.279           ms/op
ClientPb.listUser                       sample  199862   4.801 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.988           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.309           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.423           ms/op
