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
# Warmup Iteration   1: 1.543 ops/ms
# Warmup Iteration   2: 3.422 ops/ms
# Warmup Iteration   3: 7.031 ops/ms
Iteration   1: 7.330 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.808 ±(99.9%) 7.551 ops/ms [Average]
  (min, avg, max) = (7.330, 7.808, 8.054), stdev = 0.414
  CI (99.9%): [0.257, 15.359] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 6.908 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.351 ops/ms
Iteration   2: 8.683 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.516 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (8.351, 8.516, 8.683), stdev = 0.166
  CI (99.9%): [5.493, 11.539] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 6.699 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 8.126 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.026 ±(99.9%) 4.466 ops/ms [Average]
  (min, avg, max) = (7.747, 8.026, 8.205), stdev = 0.245
  CI (99.9%): [3.560, 12.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 5.806 ops/ms
# Warmup Iteration   3: 6.702 ops/ms
Iteration   1: 7.093 ops/ms
Iteration   2: 7.003 ops/ms
Iteration   3: 7.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.138 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (7.003, 7.138, 7.319), stdev = 0.163
  CI (99.9%): [4.170, 10.106] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.779 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.013 ms/op
Iteration   1: 3.821 ±(99.9%) 0.009 ms/op
Iteration   2: 3.921 ±(99.9%) 0.009 ms/op
Iteration   3: 3.748 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.830 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (3.748, 3.830, 3.921), stdev = 0.087
  CI (99.9%): [2.243, 5.417] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.576 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.007 ms/op
Iteration   1: 3.698 ±(99.9%) 0.010 ms/op
Iteration   2: 3.757 ±(99.9%) 0.009 ms/op
Iteration   3: 3.624 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.693 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.624, 3.693, 3.757), stdev = 0.067
  CI (99.9%): [2.476, 4.910] (assumes normal distribution)


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
# Warmup Iteration   1: 10.919 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.008 ms/op
Iteration   1: 3.947 ±(99.9%) 0.006 ms/op
Iteration   2: 3.864 ±(99.9%) 0.013 ms/op
Iteration   3: 3.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.907 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.864, 3.907, 3.947), stdev = 0.041
  CI (99.9%): [3.150, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 12.911 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.502 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.012 ms/op
Iteration   1: 4.592 ±(99.9%) 0.016 ms/op
Iteration   2: 4.424 ±(99.9%) 0.015 ms/op
Iteration   3: 4.559 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.525 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (4.424, 4.525, 4.592), stdev = 0.089
  CI (99.9%): [2.903, 6.147] (assumes normal distribution)


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
# Warmup Iteration   1: 12.261 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.977 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.535 ±(99.9%) 0.021 ms/op
Iteration   1: 4.008 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.792 ms/op
                 createUser·p0.999:  13.599 ms/op
                 createUser·p0.9999: 26.281 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  25.362 ms/op
                 createUser·p0.9999: 27.592 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 4.062 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   8.372 ms/op
                 createUser·p0.999:  16.709 ms/op
                 createUser·p0.9999: 31.691 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238317
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 308 
    [ 2.500,  5.000) = 224918 
    [ 5.000,  7.500) = 10265 
    [ 7.500, 10.000) = 2140 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     29.966 ms/op
     p(99.9990) =     32.251 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 12.394 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.827 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
Iteration   1: 3.815 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  13.725 ms/op
                 existUser·p0.9999: 25.337 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.820 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.765 ms/op
                 existUser·p0.999:  25.625 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 29.891 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251634
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 236 
    [ 2.500,  5.000) = 244422 
    [ 5.000,  7.500) = 5257 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.925 ms/op
     p(99.9900) =     28.929 ms/op
     p(99.9990) =     30.523 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 13.150 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
Iteration   1: 4.177 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   6.894 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  17.316 ms/op
                 getUser·p0.9999: 32.976 ms/op
                 getUser·p1.00:   34.669 ms/op

Iteration   2: 3.865 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.195 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  13.169 ms/op
                 getUser·p0.9999: 28.391 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 4.013 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  27.687 ms/op
                 getUser·p0.9999: 30.639 ms/op
                 getUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239188
  mean =      4.014 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 223887 
    [ 5.000,  7.500) = 11353 
    [ 7.500, 10.000) = 2885 
    [10.000, 12.500) = 637 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     17.414 ms/op
     p(99.9900) =     30.936 ms/op
     p(99.9990) =     34.264 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 12.740 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.218 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.017 ms/op
Iteration   1: 4.768 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   9.513 ms/op
                 listUser·p0.999:  24.019 ms/op
                 listUser·p0.9999: 28.344 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   2: 4.688 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 20.486 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.684 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   9.303 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.978 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203552
  mean =      4.713 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 176969 
    [ 5.000,  7.500) = 20767 
    [ 7.500, 10.000) = 4450 
    [10.000, 12.500) = 722 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     26.245 ms/op
     p(99.9990) =     28.856 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.808 ± 7.551  ops/ms
ClientPb.existUser                       thrpt       3   8.516 ± 3.023  ops/ms
ClientPb.getUser                         thrpt       3   8.026 ± 4.466  ops/ms
ClientPb.listUser                        thrpt       3   7.138 ± 2.968  ops/ms
ClientPb.createUser                       avgt       3   3.830 ± 1.587   ms/op
ClientPb.existUser                        avgt       3   3.693 ± 1.217   ms/op
ClientPb.getUser                          avgt       3   3.907 ± 0.757   ms/op
ClientPb.listUser                         avgt       3   4.525 ± 1.622   ms/op
ClientPb.createUser                     sample  238317   4.026 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.706           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.433           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.966           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  251634   3.815 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.925           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.929           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  239188   4.014 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.311           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.382           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.118           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  203552   4.713 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.364           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.245           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.000           ms/op
