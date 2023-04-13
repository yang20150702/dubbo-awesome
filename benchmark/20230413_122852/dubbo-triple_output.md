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
# Warmup Iteration   1: 1.943 ops/ms
# Warmup Iteration   2: 5.038 ops/ms
# Warmup Iteration   3: 8.655 ops/ms
Iteration   1: 8.912 ops/ms
Iteration   2: 8.931 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.101 ±(99.9%) 5.680 ops/ms [Average]
  (min, avg, max) = (8.912, 9.101, 9.461), stdev = 0.311
  CI (99.9%): [3.421, 14.781] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.394 ops/ms
# Warmup Iteration   2: 8.531 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 9.471 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.668 ±(99.9%) 5.247 ops/ms [Average]
  (min, avg, max) = (9.471, 9.668, 9.998), stdev = 0.288
  CI (99.9%): [4.421, 14.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.299 ops/ms
# Warmup Iteration   2: 8.526 ops/ms
# Warmup Iteration   3: 8.754 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.533 ±(99.9%) 3.955 ops/ms [Average]
  (min, avg, max) = (9.377, 9.533, 9.781), stdev = 0.217
  CI (99.9%): [5.578, 13.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.045 ops/ms
# Warmup Iteration   2: 7.287 ops/ms
# Warmup Iteration   3: 7.890 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 8.000 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.968 ±(99.9%) 3.239 ops/ms [Average]
  (min, avg, max) = (7.777, 7.968, 8.127), stdev = 0.178
  CI (99.9%): [4.729, 11.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.533 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.005 ms/op
Iteration   1: 3.457 ±(99.9%) 0.005 ms/op
Iteration   2: 3.416 ±(99.9%) 0.008 ms/op
Iteration   3: 3.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.434 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.416, 3.434, 3.457), stdev = 0.021
  CI (99.9%): [3.048, 3.821] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.003 ms/op
Iteration   1: 3.267 ±(99.9%) 0.010 ms/op
Iteration   2: 3.348 ±(99.9%) 0.007 ms/op
Iteration   3: 3.232 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.232, 3.283, 3.348), stdev = 0.059
  CI (99.9%): [2.204, 4.361] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.978 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.005 ms/op
Iteration   1: 3.542 ±(99.9%) 0.005 ms/op
Iteration   2: 3.432 ±(99.9%) 0.006 ms/op
Iteration   3: 3.384 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.452 ±(99.9%) 1.481 ms/op [Average]
  (min, avg, max) = (3.384, 3.452, 3.542), stdev = 0.081
  CI (99.9%): [1.972, 4.933] (assumes normal distribution)


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
# Warmup Iteration   1: 10.323 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
Iteration   2: 4.070 ±(99.9%) 0.007 ms/op
Iteration   3: 3.956 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.986 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.932, 3.986, 4.070), stdev = 0.074
  CI (99.9%): [2.643, 5.330] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.238 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.247 ms/op
                 createUser·p0.999:  18.435 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  21.915 ms/op
                 createUser·p0.9999: 25.093 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.519 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  17.869 ms/op
                 createUser·p0.9999: 27.386 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277982
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8403 
    [ 2.500,  5.000) = 262705 
    [ 5.000,  7.500) = 5577 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     28.188 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.008 ms/op
Iteration   1: 3.369 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  18.936 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.745 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  19.192 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 27.840 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286269
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12855 
    [ 2.500,  5.000) = 268033 
    [ 5.000,  7.500) = 4439 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     26.456 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.224 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.009 ms/op
Iteration   1: 3.484 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  22.983 ms/op
                 getUser·p0.9999: 33.417 ms/op
                 getUser·p1.00:   38.076 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 27.227 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.396 ms/op
                 getUser·p0.999:  21.203 ms/op
                 getUser·p0.9999: 28.666 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273767
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6368 
    [ 2.500,  5.000) = 258626 
    [ 5.000,  7.500) = 7335 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.872 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     21.569 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     37.963 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 11.555 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  19.371 ms/op
                 listUser·p0.9999: 24.488 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  16.837 ms/op
                 listUser·p0.9999: 23.399 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 3.971 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.344 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 15.925 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239004
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 230792 
    [ 5.000,  7.500) = 5562 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.082 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.101 ± 5.680  ops/ms
ClientPb.existUser                       thrpt       3   9.668 ± 5.247  ops/ms
ClientPb.getUser                         thrpt       3   9.533 ± 3.955  ops/ms
ClientPb.listUser                        thrpt       3   7.968 ± 3.239  ops/ms
ClientPb.createUser                       avgt       3   3.434 ± 0.386   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 1.078   ms/op
ClientPb.getUser                          avgt       3   3.452 ± 1.481   ms/op
ClientPb.listUser                         avgt       3   3.986 ± 1.343   ms/op
ClientPb.createUser                     sample  277982   3.450 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.121           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.592           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  286269   3.353 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.456           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  273767   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.872           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.967           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.076           ms/op
ClientPb.listUser                       sample  239004   4.011 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.150           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.166           ms/op
