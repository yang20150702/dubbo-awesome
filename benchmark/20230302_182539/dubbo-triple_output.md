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
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 5.052 ops/ms
# Warmup Iteration   3: 8.386 ops/ms
Iteration   1: 8.937 ops/ms
Iteration   2: 8.797 ops/ms
Iteration   3: 9.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.014 ±(99.9%) 4.815 ops/ms [Average]
  (min, avg, max) = (8.797, 9.014, 9.308), stdev = 0.264
  CI (99.9%): [4.199, 13.829] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.829 ops/ms
Iteration   2: 9.545 ops/ms
Iteration   3: 10.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 4.432 ops/ms [Average]
  (min, avg, max) = (9.545, 9.801, 10.028), stdev = 0.243
  CI (99.9%): [5.369, 14.233] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 8.482 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.215 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.294 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (9.078, 9.294, 9.587), stdev = 0.263
  CI (99.9%): [4.493, 14.094] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 6.909 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 7.544 ops/ms
Iteration   3: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.840 ±(99.9%) 4.789 ops/ms [Average]
  (min, avg, max) = (7.544, 7.840, 8.044), stdev = 0.262
  CI (99.9%): [3.052, 12.629] (assumes normal distribution)


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
# Warmup Iteration   1: 9.453 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.004 ms/op
Iteration   1: 3.422 ±(99.9%) 0.012 ms/op
Iteration   2: 3.452 ±(99.9%) 0.007 ms/op
Iteration   3: 3.467 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.447 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.422, 3.447, 3.467), stdev = 0.023
  CI (99.9%): [3.026, 3.868] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.395 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.004 ms/op
Iteration   1: 3.406 ±(99.9%) 0.004 ms/op
Iteration   2: 3.318 ±(99.9%) 0.006 ms/op
Iteration   3: 3.375 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.366 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.318, 3.366, 3.406), stdev = 0.045
  CI (99.9%): [2.552, 4.181] (assumes normal distribution)


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
# Warmup Iteration   1: 9.944 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.004 ms/op
Iteration   1: 3.919 ±(99.9%) 0.009 ms/op
Iteration   2: 3.343 ±(99.9%) 0.006 ms/op
Iteration   3: 3.486 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.583 ±(99.9%) 5.467 ms/op [Average]
  (min, avg, max) = (3.343, 3.583, 3.919), stdev = 0.300
  CI (99.9%): [≈ 0, 9.049] (assumes normal distribution)


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
# Warmup Iteration   1: 10.094 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
Iteration   2: 3.998 ±(99.9%) 0.009 ms/op
Iteration   3: 3.973 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.987 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.973, 3.987, 3.998), stdev = 0.013
  CI (99.9%): [3.752, 4.223] (assumes normal distribution)


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
# Warmup Iteration   1: 9.819 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   7.256 ms/op
                 createUser·p0.999:  19.962 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.629 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.298 ms/op
                 createUser·p0.999:  23.409 ms/op
                 createUser·p0.9999: 26.614 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.156 ms/op
                 createUser·p0.999:  17.732 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271912
  mean =      3.531 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3640 
    [ 2.500,  5.000) = 260955 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     18.984 ms/op
     p(99.9900) =     25.685 ms/op
     p(99.9990) =     27.335 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.805 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
Iteration   1: 3.293 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 22.521 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  18.504 ms/op
                 existUser·p0.9999: 21.338 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  13.983 ms/op
                 existUser·p0.9999: 23.535 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282865
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7970 
    [ 2.500,  5.000) = 269101 
    [ 5.000,  7.500) = 4722 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.469 ms/op
     p(99.9900) =     22.633 ms/op
     p(99.9990) =     24.664 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 9.684 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.009 ms/op
Iteration   1: 3.525 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  16.191 ms/op
                 getUser·p0.9999: 27.687 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 3.628 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  22.001 ms/op
                 getUser·p0.9999: 25.008 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.494 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  18.399 ms/op
                 getUser·p0.9999: 26.537 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270455
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 619 
    [ 2.500,  5.000) = 257757 
    [ 5.000,  7.500) = 9839 
    [ 7.500, 10.000) = 1698 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     18.240 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 10.906 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.013 ms/op
Iteration   1: 4.125 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  21.490 ms/op
                 listUser·p0.9999: 26.328 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.076 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.748 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.046 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  14.547 ms/op
                 listUser·p0.9999: 15.995 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235127
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 226673 
    [ 5.000,  7.500) = 6260 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.710 ms/op
     p(99.9900) =     25.641 ms/op
     p(99.9990) =     26.868 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.014 ± 4.815  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 4.432  ops/ms
ClientPb.getUser                         thrpt       3   9.294 ± 4.801  ops/ms
ClientPb.listUser                        thrpt       3   7.840 ± 4.789  ops/ms
ClientPb.createUser                       avgt       3   3.447 ± 0.421   ms/op
ClientPb.existUser                        avgt       3   3.366 ± 0.814   ms/op
ClientPb.getUser                          avgt       3   3.583 ± 5.467   ms/op
ClientPb.listUser                         avgt       3   3.987 ± 0.236   ms/op
ClientPb.createUser                     sample  271912   3.531 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.329           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.984           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.685           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  282865   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.633           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.330           ms/op
ClientPb.getUser                        sample  270455   3.548 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.223           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.240           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  235127   4.082 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.710           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.641           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
