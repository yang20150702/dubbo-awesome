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
# Warmup Iteration   1: 2.388 ops/ms
# Warmup Iteration   2: 6.063 ops/ms
# Warmup Iteration   3: 8.830 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.770 ±(99.9%) 7.528 ops/ms [Average]
  (min, avg, max) = (9.296, 9.770, 10.050), stdev = 0.413
  CI (99.9%): [2.241, 17.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ops/ms
# Warmup Iteration   2: 9.036 ops/ms
# Warmup Iteration   3: 10.228 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.141 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.169 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (10.139, 10.169, 10.227), stdev = 0.050
  CI (99.9%): [9.253, 11.085] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.252 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 10.138 ops/ms
Iteration   2: 10.088 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.994 ±(99.9%) 3.775 ops/ms [Average]
  (min, avg, max) = (9.757, 9.994, 10.138), stdev = 0.207
  CI (99.9%): [6.219, 13.769] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 7.798 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.675 ops/ms
Iteration   2: 8.586 ops/ms
Iteration   3: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.589 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (8.505, 8.589, 8.675), stdev = 0.085
  CI (99.9%): [7.037, 10.141] (assumes normal distribution)


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
# Warmup Iteration   1: 7.560 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.004 ms/op
Iteration   1: 3.278 ±(99.9%) 0.007 ms/op
Iteration   2: 3.204 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.217 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.169, 3.217, 3.278), stdev = 0.056
  CI (99.9%): [2.201, 4.233] (assumes normal distribution)


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
# Warmup Iteration   1: 7.385 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.004 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.074 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (2.983, 3.074, 3.145), stdev = 0.083
  CI (99.9%): [1.558, 4.590] (assumes normal distribution)


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
# Warmup Iteration   1: 8.255 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.004 ms/op
Iteration   1: 3.163 ±(99.9%) 0.004 ms/op
Iteration   2: 3.271 ±(99.9%) 0.006 ms/op
Iteration   3: 3.252 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.229 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (3.163, 3.229, 3.271), stdev = 0.058
  CI (99.9%): [2.174, 4.284] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.910 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.009 ms/op
Iteration   1: 3.733 ±(99.9%) 0.011 ms/op
Iteration   2: 3.725 ±(99.9%) 0.007 ms/op
Iteration   3: 3.664 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.664, 3.708, 3.733), stdev = 0.038
  CI (99.9%): [3.021, 4.394] (assumes normal distribution)


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
# Warmup Iteration   1: 7.846 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.416 ms/op
                 createUser·p0.99:   5.536 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  10.404 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.606 ms/op
                 createUser·p0.9999: 23.457 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303665
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16129 
    [ 2.500,  5.000) = 282636 
    [ 5.000,  7.500) = 4149 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     17.749 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     24.443 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 7.560 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  14.516 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.432 ms/op
                 existUser·p0.999:  16.040 ms/op
                 existUser·p0.9999: 24.824 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 22.209 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305318
  mean =      3.141 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21405 
    [ 2.500,  5.000) = 279215 
    [ 5.000,  7.500) = 3952 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     15.936 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
Iteration   1: 3.313 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  18.522 ms/op
                 getUser·p0.9999: 21.847 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 21.899 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295561
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12476 
    [ 2.500,  5.000) = 276477 
    [ 5.000,  7.500) = 5658 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 175 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     15.076 ms/op
     p(99.9900) =     21.805 ms/op
     p(99.9990) =     23.005 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.442 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.012 ms/op
Iteration   1: 3.823 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.522 ms/op
                 listUser·p0.9999: 19.288 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 3.842 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.786 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 20.464 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251344
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 242238 
    [ 5.000,  7.500) = 7261 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.390 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.315 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.770 ± 7.528  ops/ms
ClientPb.existUser                       thrpt       3  10.169 ± 0.916  ops/ms
ClientPb.getUser                         thrpt       3   9.994 ± 3.775  ops/ms
ClientPb.listUser                        thrpt       3   8.589 ± 1.552  ops/ms
ClientPb.createUser                       avgt       3   3.217 ± 1.016   ms/op
ClientPb.existUser                        avgt       3   3.074 ± 1.516   ms/op
ClientPb.getUser                          avgt       3   3.229 ± 1.055   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.686   ms/op
ClientPb.createUser                     sample  303665   3.159 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.708           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.035           ms/op
ClientPb.existUser                      sample  305318   3.141 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.936           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.625           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  295561   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.405           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.805           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.364           ms/op
ClientPb.listUser                       sample  251344   3.817 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.390           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.430           ms/op
