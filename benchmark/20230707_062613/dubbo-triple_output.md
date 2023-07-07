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
# Warmup Iteration   1: 1.611 ops/ms
# Warmup Iteration   2: 3.368 ops/ms
# Warmup Iteration   3: 6.728 ops/ms
Iteration   1: 7.141 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.817 ±(99.9%) 10.817 ops/ms [Average]
  (min, avg, max) = (7.141, 7.817, 8.251), stdev = 0.593
  CI (99.9%): [≈ 0, 18.633] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.351 ops/ms
# Warmup Iteration   2: 6.869 ops/ms
# Warmup Iteration   3: 7.543 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.172 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (8.040, 8.172, 8.314), stdev = 0.137
  CI (99.9%): [5.670, 10.675] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.122 ops/ms
# Warmup Iteration   2: 6.391 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.631 ops/ms
Iteration   2: 8.125 ops/ms
Iteration   3: 7.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.863 ±(99.9%) 4.537 ops/ms [Average]
  (min, avg, max) = (7.631, 7.863, 8.125), stdev = 0.249
  CI (99.9%): [3.326, 12.400] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.013 ops/ms
# Warmup Iteration   2: 5.359 ops/ms
# Warmup Iteration   3: 6.689 ops/ms
Iteration   1: 6.570 ops/ms
Iteration   2: 6.665 ops/ms
Iteration   3: 6.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.587 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (6.526, 6.587, 6.665), stdev = 0.071
  CI (99.9%): [5.285, 7.890] (assumes normal distribution)


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
# Warmup Iteration   1: 15.018 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.562 ±(99.9%) 0.008 ms/op
Iteration   1: 4.027 ±(99.9%) 0.005 ms/op
Iteration   2: 4.101 ±(99.9%) 0.009 ms/op
Iteration   3: 3.975 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.034 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (3.975, 4.034, 4.101), stdev = 0.063
  CI (99.9%): [2.879, 5.189] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.827 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.009 ms/op
Iteration   1: 3.849 ±(99.9%) 0.005 ms/op
Iteration   2: 3.874 ±(99.9%) 0.005 ms/op
Iteration   3: 3.807 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.843 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (3.807, 3.843, 3.874), stdev = 0.034
  CI (99.9%): [3.219, 4.468] (assumes normal distribution)


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
# Warmup Iteration   1: 14.447 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.005 ms/op
Iteration   1: 4.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.896 ±(99.9%) 0.013 ms/op
Iteration   3: 3.975 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.005 ±(99.9%) 2.325 ms/op [Average]
  (min, avg, max) = (3.896, 4.005, 4.145), stdev = 0.127
  CI (99.9%): [1.680, 6.330] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.659 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.448 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.029 ±(99.9%) 0.007 ms/op
Iteration   1: 4.755 ±(99.9%) 0.011 ms/op
Iteration   2: 4.678 ±(99.9%) 0.019 ms/op
Iteration   3: 4.836 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.756 ±(99.9%) 1.440 ms/op [Average]
  (min, avg, max) = (4.678, 4.756, 4.836), stdev = 0.079
  CI (99.9%): [3.316, 6.196] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.136 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.558 ±(99.9%) 0.020 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  24.949 ms/op
                 createUser·p0.9999: 26.652 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 4.271 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   8.427 ms/op
                 createUser·p0.999:  20.171 ms/op
                 createUser·p0.9999: 36.635 ms/op
                 createUser·p1.00:   37.880 ms/op

Iteration   3: 4.003 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  31.559 ms/op
                 createUser·p0.9999: 33.883 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234354
  mean =      4.095 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 205 
    [ 2.500,  5.000) = 219607 
    [ 5.000,  7.500) = 12137 
    [ 7.500, 10.000) = 1522 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.565 ms/op
     p(99.9000) =     25.449 ms/op
     p(99.9900) =     35.828 ms/op
     p(99.9990) =     37.522 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.661 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  14.380 ms/op
                 existUser·p0.9999: 29.646 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  24.893 ms/op
                 existUser·p0.9999: 27.905 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.130 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 30.377 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242162
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 233114 
    [ 5.000,  7.500) = 6866 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.363 ms/op
     p(99.9900) =     29.772 ms/op
     p(99.9990) =     31.233 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.738 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.851 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.015 ms/op
Iteration   1: 4.394 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   7.152 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  15.423 ms/op
                 getUser·p0.9999: 26.645 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  19.853 ms/op
                 getUser·p0.9999: 27.957 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 4.172 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  27.525 ms/op
                 getUser·p0.9999: 31.992 ms/op
                 getUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227643
  mean =      4.216 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 212624 
    [ 5.000,  7.500) = 10874 
    [ 7.500, 10.000) = 3159 
    [10.000, 12.500) = 632 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     32.479 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 13.922 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 6.031 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.090 ±(99.9%) 0.022 ms/op
Iteration   1: 5.040 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  25.119 ms/op
                 listUser·p0.9999: 28.191 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.920 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.082 ms/op
                 listUser·p0.999:  21.819 ms/op
                 listUser·p0.9999: 29.377 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   3: 4.852 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 21.700 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194268
  mean =      4.936 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 141959 
    [ 5.000,  7.500) = 45474 
    [ 7.500, 10.000) = 5258 
    [10.000, 12.500) = 876 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     22.214 ms/op
     p(99.9900) =     28.494 ms/op
     p(99.9990) =     31.015 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.817 ± 10.817  ops/ms
ClientPb.existUser                       thrpt       3   8.172 ±  2.502  ops/ms
ClientPb.getUser                         thrpt       3   7.863 ±  4.537  ops/ms
ClientPb.listUser                        thrpt       3   6.587 ±  1.302  ops/ms
ClientPb.createUser                       avgt       3   4.034 ±  1.155   ms/op
ClientPb.existUser                        avgt       3   3.843 ±  0.624   ms/op
ClientPb.getUser                          avgt       3   4.005 ±  2.325   ms/op
ClientPb.listUser                         avgt       3   4.756 ±  1.440   ms/op
ClientPb.createUser                     sample  234354   4.095 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.864            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.565            ms/op
ClientPb.createUser:createUser·p0.999   sample          25.449            ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.828            ms/op
ClientPb.createUser:createUser·p1.00    sample          37.880            ms/op
ClientPb.existUser                      sample  242162   3.961 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.883            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.078            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.363            ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.772            ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654            ms/op
ClientPb.getUser                        sample  227643   4.216 ±  0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.708            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.006            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.333            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.831            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.890            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702            ms/op
ClientPb.listUser                       sample  194268   4.936 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.538            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.455            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.601            ms/op
ClientPb.listUser:listUser·p0.999       sample          22.214            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.494            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899            ms/op
