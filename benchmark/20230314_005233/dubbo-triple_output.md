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
# Warmup Iteration   1: 1.237 ops/ms
# Warmup Iteration   2: 3.000 ops/ms
# Warmup Iteration   3: 5.895 ops/ms
Iteration   1: 6.111 ops/ms
Iteration   2: 6.333 ops/ms
Iteration   3: 6.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.258 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (6.111, 6.258, 6.333), stdev = 0.127
  CI (99.9%): [3.941, 8.575] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 5.561 ops/ms
# Warmup Iteration   3: 6.210 ops/ms
Iteration   1: 6.377 ops/ms
Iteration   2: 6.517 ops/ms
Iteration   3: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.492 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (6.377, 6.492, 6.582), stdev = 0.105
  CI (99.9%): [4.583, 8.401] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.700 ops/ms
# Warmup Iteration   2: 5.028 ops/ms
# Warmup Iteration   3: 6.041 ops/ms
Iteration   1: 6.104 ops/ms
Iteration   2: 6.169 ops/ms
Iteration   3: 6.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.170 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (6.104, 6.170, 6.237), stdev = 0.067
  CI (99.9%): [4.953, 7.387] (assumes normal distribution)


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
# Warmup Iteration   1: 1.819 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 5.755 ops/ms
Iteration   1: 5.679 ops/ms
Iteration   2: 5.468 ops/ms
Iteration   3: 5.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.611 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (5.468, 5.611, 5.688), stdev = 0.124
  CI (99.9%): [3.341, 7.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.023 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.917 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.091 ±(99.9%) 0.017 ms/op
Iteration   1: 5.274 ±(99.9%) 0.010 ms/op
Iteration   2: 5.306 ±(99.9%) 0.012 ms/op
Iteration   3: 5.084 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.222 ±(99.9%) 2.194 ms/op [Average]
  (min, avg, max) = (5.084, 5.222, 5.306), stdev = 0.120
  CI (99.9%): [3.027, 7.416] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.952 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.487 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.016 ms/op
Iteration   1: 4.841 ±(99.9%) 0.011 ms/op
Iteration   2: 4.714 ±(99.9%) 0.016 ms/op
Iteration   3: 4.680 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.745 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (4.680, 4.745, 4.841), stdev = 0.085
  CI (99.9%): [3.192, 6.299] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.573 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.186 ±(99.9%) 0.011 ms/op
Iteration   1: 4.963 ±(99.9%) 0.014 ms/op
Iteration   2: 5.116 ±(99.9%) 0.019 ms/op
Iteration   3: 4.852 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.977 ±(99.9%) 2.412 ms/op [Average]
  (min, avg, max) = (4.852, 4.977, 5.116), stdev = 0.132
  CI (99.9%): [2.565, 7.389] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.509 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.913 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.015 ms/op
Iteration   1: 5.668 ±(99.9%) 0.015 ms/op
Iteration   2: 6.009 ±(99.9%) 0.012 ms/op
Iteration   3: 5.979 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.886 ±(99.9%) 3.442 ms/op [Average]
  (min, avg, max) = (5.668, 5.886, 6.009), stdev = 0.189
  CI (99.9%): [2.443, 9.328] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.340 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.291 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.022 ms/op
Iteration   1: 4.858 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   5.923 ms/op
                 createUser·p0.95:   6.685 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  15.791 ms/op
                 createUser·p0.9999: 30.029 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   2: 5.189 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 26.335 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 5.146 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.042 ms/op
                 createUser·p0.50:   4.784 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  24.867 ms/op
                 createUser·p0.9999: 31.082 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189533
  mean =      5.060 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 114474 
    [ 5.000,  7.500) = 68524 
    [ 7.500, 10.000) = 5117 
    [10.000, 12.500) = 834 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.042 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     22.129 ms/op
     p(99.9900) =     29.922 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 14.103 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.474 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.016 ms/op
Iteration   1: 4.893 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  17.414 ms/op
                 existUser·p0.9999: 30.140 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   2: 4.761 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   4.489 ms/op
                 existUser·p0.90:   5.775 ms/op
                 existUser·p0.95:   6.734 ms/op
                 existUser·p0.99:   8.847 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 26.331 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 4.521 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   4.350 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.307 ms/op
                 existUser·p0.999:  20.644 ms/op
                 existUser·p0.9999: 29.554 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203374
  mean =      4.720 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 157726 
    [ 5.000,  7.500) = 39872 
    [ 7.500, 10.000) = 4674 
    [10.000, 12.500) = 628 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     29.764 ms/op
     p(99.9990) =     30.990 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 15.734 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.711 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.177 ±(99.9%) 0.017 ms/op
Iteration   1: 5.293 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.454 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   11.780 ms/op
                 getUser·p0.999:  21.732 ms/op
                 getUser·p0.9999: 29.186 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   2: 5.074 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.038 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   7.111 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  23.173 ms/op
                 getUser·p0.9999: 26.251 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 4.896 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   9.049 ms/op
                 getUser·p0.999:  18.038 ms/op
                 getUser·p0.9999: 29.210 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188653
  mean =      5.083 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 116344 
    [ 5.000,  7.500) = 64230 
    [ 7.500, 10.000) = 5886 
    [10.000, 12.500) = 1293 
    [12.500, 15.000) = 408 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     21.705 ms/op
     p(99.9900) =     28.751 ms/op
     p(99.9990) =     31.071 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 17.842 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.523 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.021 ms/op
Iteration   1: 5.743 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.232 ms/op
                 listUser·p0.999:  23.441 ms/op
                 listUser·p0.9999: 27.446 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 5.863 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.974 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  24.264 ms/op
                 listUser·p0.9999: 32.640 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 5.731 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  25.043 ms/op
                 listUser·p0.9999: 28.624 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165936
  mean =      5.779 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 30319 
    [ 5.000,  7.500) = 124552 
    [ 7.500, 10.000) = 8214 
    [10.000, 12.500) = 1993 
    [12.500, 15.000) = 303 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.728 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     23.988 ms/op
     p(99.9900) =     31.118 ms/op
     p(99.9990) =     33.009 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.258 ± 2.317  ops/ms
ClientPb.existUser                       thrpt       3   6.492 ± 1.909  ops/ms
ClientPb.getUser                         thrpt       3   6.170 ± 1.217  ops/ms
ClientPb.listUser                        thrpt       3   5.611 ± 2.271  ops/ms
ClientPb.createUser                       avgt       3   5.222 ± 2.194   ms/op
ClientPb.existUser                        avgt       3   4.745 ± 1.553   ms/op
ClientPb.getUser                          avgt       3   4.977 ± 2.412   ms/op
ClientPb.listUser                         avgt       3   5.886 ± 3.442   ms/op
ClientPb.createUser                     sample  189533   5.060 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.042           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.021           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.129           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.922           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.556           ms/op
ClientPb.existUser                      sample  203374   4.720 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.066           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.619           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.847           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.431           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.764           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  188653   5.083 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.242           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.256           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.705           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  165936   5.779 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.728           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.879           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.988           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.118           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
