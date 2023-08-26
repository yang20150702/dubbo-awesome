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
# Warmup Iteration   1: 1.825 ops/ms
# Warmup Iteration   2: 3.876 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 6.959 ops/ms
Iteration   2: 8.164 ops/ms
Iteration   3: 8.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.794 ±(99.9%) 13.216 ops/ms [Average]
  (min, avg, max) = (6.959, 7.794, 8.258), stdev = 0.724
  CI (99.9%): [≈ 0, 21.010] (assumes normal distribution)


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
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 7.398 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.440 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.296 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (8.203, 8.296, 8.440), stdev = 0.127
  CI (99.9%): [5.987, 10.604] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.107 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (7.939, 8.107, 8.240), stdev = 0.153
  CI (99.9%): [5.312, 10.901] (assumes normal distribution)


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
# Warmup Iteration   1: 2.499 ops/ms
# Warmup Iteration   2: 6.004 ops/ms
# Warmup Iteration   3: 6.719 ops/ms
Iteration   1: 6.761 ops/ms
Iteration   2: 6.968 ops/ms
Iteration   3: 7.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.981 ±(99.9%) 4.143 ops/ms [Average]
  (min, avg, max) = (6.761, 6.981, 7.214), stdev = 0.227
  CI (99.9%): [2.838, 11.124] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.442 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.005 ms/op
Iteration   1: 3.996 ±(99.9%) 0.008 ms/op
Iteration   2: 3.771 ±(99.9%) 0.010 ms/op
Iteration   3: 4.006 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.924 ±(99.9%) 2.424 ms/op [Average]
  (min, avg, max) = (3.771, 3.924, 4.006), stdev = 0.133
  CI (99.9%): [1.501, 6.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.427 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.005 ms/op
Iteration   1: 3.714 ±(99.9%) 0.013 ms/op
Iteration   2: 3.685 ±(99.9%) 0.004 ms/op
Iteration   3: 3.730 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.709 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.685, 3.709, 3.730), stdev = 0.023
  CI (99.9%): [3.294, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 12.401 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.006 ms/op
Iteration   1: 3.914 ±(99.9%) 0.007 ms/op
Iteration   2: 3.818 ±(99.9%) 0.008 ms/op
Iteration   3: 3.960 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.897 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.818, 3.897, 3.960), stdev = 0.073
  CI (99.9%): [2.571, 5.224] (assumes normal distribution)


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
# Warmup Iteration   1: 14.194 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.375 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.005 ms/op
Iteration   1: 4.677 ±(99.9%) 0.009 ms/op
Iteration   2: 4.606 ±(99.9%) 0.012 ms/op
Iteration   3: 4.768 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.684 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (4.606, 4.684, 4.768), stdev = 0.081
  CI (99.9%): [3.198, 6.169] (assumes normal distribution)


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
# Warmup Iteration   1: 13.577 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.330 ±(99.9%) 0.017 ms/op
Iteration   1: 4.097 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 25.997 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.882 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  13.778 ms/op
                 createUser·p0.9999: 26.953 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.908 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  29.295 ms/op
                 createUser·p0.9999: 73.638 ms/op
                 createUser·p1.00:   74.449 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242359
  mean =      3.960 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 230410 
    [ 5.000, 10.000) = 10987 
    [10.000, 15.000) = 674 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 112 
    [25.000, 30.000) = 86 
    [30.000, 35.000) = 42 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 8 
    [65.000, 70.000) = 2 
    [70.000, 75.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     65.281 ms/op
     p(99.9990) =     74.318 ms/op
     p(99.9999) =     74.449 ms/op
    p(100.0000) =     74.449 ms/op


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
# Warmup Iteration   1: 13.275 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
Iteration   1: 3.950 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   8.031 ms/op
                 existUser·p0.999:  22.184 ms/op
                 existUser·p0.9999: 27.647 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  12.335 ms/op
                 existUser·p0.9999: 24.419 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 26.670 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245438
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 379 
    [ 2.500,  5.000) = 233209 
    [ 5.000,  7.500) = 9455 
    [ 7.500, 10.000) = 1662 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     26.655 ms/op
     p(99.9990) =     28.160 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 13.241 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.014 ms/op
Iteration   1: 4.380 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  23.429 ms/op
                 getUser·p0.9999: 32.400 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   2: 4.180 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.087 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 27.569 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  12.304 ms/op
                 getUser·p0.9999: 30.339 ms/op
                 getUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230363
  mean =      4.167 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 367 
    [ 2.500,  5.000) = 210614 
    [ 5.000,  7.500) = 14730 
    [ 7.500, 10.000) = 3602 
    [10.000, 12.500) = 699 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.607 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 14.562 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.715 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.016 ms/op
Iteration   1: 4.959 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  28.410 ms/op
                 listUser·p0.9999: 32.413 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   2: 4.733 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   8.511 ms/op
                 listUser·p0.999:  19.970 ms/op
                 listUser·p0.9999: 29.434 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   3: 4.609 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 18.157 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201488
  mean =      4.763 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 159758 
    [ 5.000,  7.500) = 35737 
    [ 7.500, 10.000) = 4580 
    [10.000, 12.500) = 790 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     31.372 ms/op
     p(99.9990) =     34.508 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.794 ± 13.216  ops/ms
ClientPb.existUser                       thrpt       3   8.296 ±  2.309  ops/ms
ClientPb.getUser                         thrpt       3   8.107 ±  2.795  ops/ms
ClientPb.listUser                        thrpt       3   6.981 ±  4.143  ops/ms
ClientPb.createUser                       avgt       3   3.924 ±  2.424   ms/op
ClientPb.existUser                        avgt       3   3.709 ±  0.416   ms/op
ClientPb.getUser                          avgt       3   3.897 ±  1.327   ms/op
ClientPb.listUser                         avgt       3   4.684 ±  1.486   ms/op
ClientPb.createUser                     sample  242359   3.960 ±  0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.733            ms/op
ClientPb.createUser:createUser·p0.999   sample          22.741            ms/op
ClientPb.createUser:createUser·p0.9999  sample          65.281            ms/op
ClientPb.createUser:createUser·p1.00    sample          74.449            ms/op
ClientPb.existUser                      sample  245438   3.908 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.391            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.956            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.455            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.499            ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.655            ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279            ms/op
ClientPb.getUser                        sample  230363   4.167 ±  0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.850            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.759            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.733            ms/op
ClientPb.getUser:getUser·p0.999         sample          21.955            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.802            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670            ms/op
ClientPb.listUser                       sample  201488   4.763 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.439            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.300            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.339            ms/op
ClientPb.listUser:listUser·p0.999       sample          19.792            ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.372            ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603            ms/op
