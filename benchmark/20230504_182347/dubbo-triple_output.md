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
# Warmup Iteration   1: 2.287 ops/ms
# Warmup Iteration   2: 5.832 ops/ms
# Warmup Iteration   3: 8.459 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.586 ops/ms
Iteration   3: 9.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.417 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (9.238, 9.417, 9.586), stdev = 0.174
  CI (99.9%): [6.242, 12.592] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.627 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.709 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 9.914 ops/ms
Iteration   3: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.806 ±(99.9%) 3.635 ops/ms [Average]
  (min, avg, max) = (9.576, 9.806, 9.929), stdev = 0.199
  CI (99.9%): [6.171, 13.441] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.900 ops/ms
# Warmup Iteration   2: 8.184 ops/ms
# Warmup Iteration   3: 9.234 ops/ms
Iteration   1: 9.335 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.482 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (9.335, 9.482, 9.612), stdev = 0.139
  CI (99.9%): [6.943, 12.021] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ops/ms
# Warmup Iteration   2: 7.301 ops/ms
# Warmup Iteration   3: 8.060 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.134 ±(99.9%) 3.659 ops/ms [Average]
  (min, avg, max) = (7.904, 8.134, 8.266), stdev = 0.201
  CI (99.9%): [4.475, 11.794] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.020 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.007 ms/op
Iteration   1: 3.469 ±(99.9%) 0.007 ms/op
Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
Iteration   3: 3.492 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.415, 3.459, 3.492), stdev = 0.040
  CI (99.9%): [2.733, 4.185] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.894 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.006 ms/op
Iteration   1: 3.404 ±(99.9%) 0.007 ms/op
Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
Iteration   3: 3.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.274 ±(99.9%) 2.052 ms/op [Average]
  (min, avg, max) = (3.199, 3.274, 3.404), stdev = 0.112
  CI (99.9%): [1.222, 5.327] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.476 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.005 ms/op
Iteration   1: 3.401 ±(99.9%) 0.005 ms/op
Iteration   2: 3.344 ±(99.9%) 0.008 ms/op
Iteration   3: 3.413 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.386 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.344, 3.386, 3.413), stdev = 0.037
  CI (99.9%): [2.709, 4.063] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.967 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.009 ms/op
Iteration   1: 3.880 ±(99.9%) 0.013 ms/op
Iteration   2: 3.864 ±(99.9%) 0.015 ms/op
Iteration   3: 4.007 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.917 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.864, 3.917, 4.007), stdev = 0.079
  CI (99.9%): [2.480, 5.353] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.437 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 24.897 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  20.824 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.361 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283590
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15548 
    [ 2.500,  5.000) = 261602 
    [ 5.000,  7.500) = 5546 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     18.331 ms/op
     p(99.9900) =     34.949 ms/op
     p(99.9990) =     36.001 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.271 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.306 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  10.995 ms/op
                 existUser·p0.9999: 22.981 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  14.185 ms/op
                 existUser·p0.9999: 25.788 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  22.985 ms/op
                 existUser·p0.9999: 27.193 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289079
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10738 
    [ 2.500,  5.000) = 272685 
    [ 5.000,  7.500) = 4781 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     12.776 ms/op
     p(99.9900) =     26.021 ms/op
     p(99.9990) =     27.794 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 8.627 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.012 ms/op
Iteration   1: 3.410 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  20.606 ms/op
                 getUser·p0.9999: 34.537 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  21.702 ms/op
                 getUser·p0.9999: 31.254 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  15.344 ms/op
                 getUser·p0.9999: 27.787 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285357
  mean =      3.361 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2235 
    [ 2.500,  5.000) = 276459 
    [ 5.000,  7.500) = 5338 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     15.438 ms/op
     p(99.9900) =     32.927 ms/op
     p(99.9990) =     34.875 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 10.854 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
Iteration   1: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  23.604 ms/op
                 listUser·p0.9999: 27.302 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 17.026 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239040
  mean =      4.014 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 230651 
    [ 5.000,  7.500) = 6006 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     16.121 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.776 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.417 ± 3.175  ops/ms
ClientPb.existUser                       thrpt       3   9.806 ± 3.635  ops/ms
ClientPb.getUser                         thrpt       3   9.482 ± 2.539  ops/ms
ClientPb.listUser                        thrpt       3   8.134 ± 3.659  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.726   ms/op
ClientPb.existUser                        avgt       3   3.274 ± 2.052   ms/op
ClientPb.getUser                          avgt       3   3.386 ± 0.677   ms/op
ClientPb.listUser                         avgt       3   3.917 ± 1.436   ms/op
ClientPb.createUser                     sample  283590   3.387 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.949           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  289079   3.319 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.776           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.017           ms/op
ClientPb.getUser                        sample  285357   3.361 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  239040   4.014 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
