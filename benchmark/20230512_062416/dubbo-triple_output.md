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
# Warmup Iteration   1: 1.025 ops/ms
# Warmup Iteration   2: 2.232 ops/ms
# Warmup Iteration   3: 4.779 ops/ms
Iteration   1: 5.016 ops/ms
Iteration   2: 5.483 ops/ms
Iteration   3: 5.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.365 ±(99.9%) 5.604 ops/ms [Average]
  (min, avg, max) = (5.016, 5.365, 5.595), stdev = 0.307
  CI (99.9%): [≈ 0, 10.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.636 ops/ms
# Warmup Iteration   2: 4.719 ops/ms
# Warmup Iteration   3: 5.487 ops/ms
Iteration   1: 5.745 ops/ms
Iteration   2: 5.692 ops/ms
Iteration   3: 5.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.742 ±(99.9%) 0.879 ops/ms [Average]
  (min, avg, max) = (5.692, 5.742, 5.788), stdev = 0.048
  CI (99.9%): [4.863, 6.621] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.464 ops/ms
# Warmup Iteration   2: 4.112 ops/ms
# Warmup Iteration   3: 5.629 ops/ms
Iteration   1: 5.586 ops/ms
Iteration   2: 5.558 ops/ms
Iteration   3: 5.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.645 ±(99.9%) 2.302 ops/ms [Average]
  (min, avg, max) = (5.558, 5.645, 5.790), stdev = 0.126
  CI (99.9%): [3.343, 7.947] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.628 ops/ms
# Warmup Iteration   2: 4.182 ops/ms
# Warmup Iteration   3: 5.013 ops/ms
Iteration   1: 4.951 ops/ms
Iteration   2: 4.903 ops/ms
Iteration   3: 4.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.949 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (4.903, 4.949, 4.992), stdev = 0.045
  CI (99.9%): [4.133, 5.765] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.276 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.896 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.011 ms/op
Iteration   1: 5.818 ±(99.9%) 0.012 ms/op
Iteration   2: 5.786 ±(99.9%) 0.014 ms/op
Iteration   3: 5.542 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.716 ±(99.9%) 2.750 ms/op [Average]
  (min, avg, max) = (5.542, 5.716, 5.818), stdev = 0.151
  CI (99.9%): [2.966, 8.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.938 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.390 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.646 ±(99.9%) 0.011 ms/op
Iteration   1: 5.253 ±(99.9%) 0.007 ms/op
Iteration   2: 5.361 ±(99.9%) 0.011 ms/op
Iteration   3: 5.187 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.267 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (5.187, 5.267, 5.361), stdev = 0.088
  CI (99.9%): [3.664, 6.870] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.460 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.658 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.691 ±(99.9%) 0.010 ms/op
Iteration   1: 5.858 ±(99.9%) 0.008 ms/op
Iteration   2: 5.652 ±(99.9%) 0.008 ms/op
Iteration   3: 5.460 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.657 ±(99.9%) 3.636 ms/op [Average]
  (min, avg, max) = (5.460, 5.657, 5.858), stdev = 0.199
  CI (99.9%): [2.021, 9.293] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.566 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 8.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.839 ±(99.9%) 0.013 ms/op
Iteration   1: 6.251 ±(99.9%) 0.019 ms/op
Iteration   2: 6.355 ±(99.9%) 0.017 ms/op
Iteration   3: 6.454 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.354 ±(99.9%) 1.856 ms/op [Average]
  (min, avg, max) = (6.251, 6.354, 6.454), stdev = 0.102
  CI (99.9%): [4.497, 8.210] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.799 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 6.906 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 6.090 ±(99.9%) 0.028 ms/op
Iteration   1: 5.657 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.396 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.905 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  25.211 ms/op
                 createUser·p0.9999: 27.843 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 5.722 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.307 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  15.205 ms/op
                 createUser·p0.9999: 34.335 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   3: 5.663 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   11.142 ms/op
                 createUser·p0.999:  31.798 ms/op
                 createUser·p0.9999: 36.411 ms/op
                 createUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168798
  mean =      5.681 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 56269 
    [ 5.000,  7.500) = 99971 
    [ 7.500, 10.000) = 9890 
    [10.000, 12.500) = 1821 
    [12.500, 15.000) = 544 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     21.633 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.194 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.144 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.411 ±(99.9%) 0.019 ms/op
Iteration   1: 5.261 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  15.929 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 5.311 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.666 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  30.110 ms/op
                 existUser·p0.9999: 37.548 ms/op
                 existUser·p1.00:   38.928 ms/op

Iteration   3: 5.283 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.365 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  27.390 ms/op
                 existUser·p0.9999: 30.731 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181564
  mean =      5.285 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 94942 
    [ 5.000,  7.500) = 77726 
    [ 7.500, 10.000) = 6885 
    [10.000, 12.500) = 1236 
    [12.500, 15.000) = 455 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.229 ms/op
     p(99.9000) =     17.349 ms/op
     p(99.9900) =     36.887 ms/op
     p(99.9990) =     38.340 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.745 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.420 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.882 ±(99.9%) 0.023 ms/op
Iteration   1: 5.769 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   12.468 ms/op
                 getUser·p0.999:  25.662 ms/op
                 getUser·p0.9999: 45.548 ms/op
                 getUser·p1.00:   45.941 ms/op

Iteration   2: 5.668 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   11.256 ms/op
                 getUser·p0.999:  25.649 ms/op
                 getUser·p0.9999: 34.124 ms/op
                 getUser·p1.00:   35.914 ms/op

Iteration   3: 5.669 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.525 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  17.167 ms/op
                 getUser·p0.9999: 28.979 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168357
  mean =      5.702 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53130 
    [ 5.000, 10.000) = 111620 
    [10.000, 15.000) = 3135 
    [15.000, 20.000) = 261 
    [20.000, 25.000) = 53 
    [25.000, 30.000) = 93 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     24.094 ms/op
     p(99.9900) =     44.302 ms/op
     p(99.9990) =     45.941 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 25.012 ±(99.9%) 0.449 ms/op
# Warmup Iteration   2: 9.969 ±(99.9%) 0.081 ms/op
# Warmup Iteration   3: 6.798 ±(99.9%) 0.031 ms/op
Iteration   1: 6.744 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.184 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  27.953 ms/op
                 listUser·p0.9999: 31.949 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   2: 6.208 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  27.132 ms/op
                 listUser·p0.9999: 31.629 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 6.305 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   12.017 ms/op
                 listUser·p0.999:  27.992 ms/op
                 listUser·p0.9999: 34.991 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149727
  mean =      6.411 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 4971 
    [ 5.000,  7.500) = 127308 
    [ 7.500, 10.000) = 13071 
    [10.000, 12.500) = 3092 
    [12.500, 15.000) = 671 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      6.054 ms/op
     p(90.0000) =      7.709 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     27.388 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.365 ± 5.604  ops/ms
ClientPb.existUser                       thrpt       3   5.742 ± 0.879  ops/ms
ClientPb.getUser                         thrpt       3   5.645 ± 2.302  ops/ms
ClientPb.listUser                        thrpt       3   4.949 ± 0.816  ops/ms
ClientPb.createUser                       avgt       3   5.716 ± 2.750   ms/op
ClientPb.existUser                        avgt       3   5.267 ± 1.603   ms/op
ClientPb.getUser                          avgt       3   5.657 ± 3.636   ms/op
ClientPb.listUser                         avgt       3   6.354 ± 1.856   ms/op
ClientPb.createUser                     sample  168798   5.681 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.061           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.043           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.633           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.324           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  181564   5.285 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.677           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.463           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.229           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.349           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.887           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.928           ms/op
ClientPb.getUser                        sample  168357   5.702 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.525           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.552           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.633           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.094           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.941           ms/op
ClientPb.listUser                       sample  149727   6.411 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.054           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
