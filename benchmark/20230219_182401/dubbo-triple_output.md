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
# Warmup Iteration   1: 0.959 ops/ms
# Warmup Iteration   2: 2.266 ops/ms
# Warmup Iteration   3: 5.251 ops/ms
Iteration   1: 5.535 ops/ms
Iteration   2: 5.797 ops/ms
Iteration   3: 5.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.769 ±(99.9%) 4.038 ops/ms [Average]
  (min, avg, max) = (5.535, 5.769, 5.975), stdev = 0.221
  CI (99.9%): [1.731, 9.806] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.722 ops/ms
# Warmup Iteration   2: 4.891 ops/ms
# Warmup Iteration   3: 6.234 ops/ms
Iteration   1: 6.153 ops/ms
Iteration   2: 6.138 ops/ms
Iteration   3: 6.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.134 ±(99.9%) 0.394 ops/ms [Average]
  (min, avg, max) = (6.110, 6.134, 6.153), stdev = 0.022
  CI (99.9%): [5.740, 6.528] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 4.681 ops/ms
# Warmup Iteration   3: 5.771 ops/ms
Iteration   1: 5.700 ops/ms
Iteration   2: 5.696 ops/ms
Iteration   3: 5.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.767 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (5.696, 5.767, 5.904), stdev = 0.119
  CI (99.9%): [3.591, 7.943] (assumes normal distribution)


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
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.657 ops/ms
# Warmup Iteration   3: 5.069 ops/ms
Iteration   1: 4.945 ops/ms
Iteration   2: 5.082 ops/ms
Iteration   3: 5.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.034 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (4.945, 5.034, 5.082), stdev = 0.077
  CI (99.9%): [3.631, 6.437] (assumes normal distribution)


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
# Warmup Iteration   1: 17.793 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.824 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.848 ±(99.9%) 0.010 ms/op
Iteration   1: 5.360 ±(99.9%) 0.011 ms/op
Iteration   2: 5.390 ±(99.9%) 0.017 ms/op
Iteration   3: 5.384 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.378 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (5.360, 5.378, 5.390), stdev = 0.015
  CI (99.9%): [5.095, 5.661] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.176 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.161 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.300 ±(99.9%) 0.008 ms/op
Iteration   1: 5.131 ±(99.9%) 0.011 ms/op
Iteration   2: 5.446 ±(99.9%) 0.010 ms/op
Iteration   3: 5.111 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.230 ±(99.9%) 3.430 ms/op [Average]
  (min, avg, max) = (5.111, 5.230, 5.446), stdev = 0.188
  CI (99.9%): [1.800, 8.659] (assumes normal distribution)


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
# Warmup Iteration   1: 18.039 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.619 ±(99.9%) 0.008 ms/op
Iteration   1: 5.703 ±(99.9%) 0.011 ms/op
Iteration   2: 5.360 ±(99.9%) 0.015 ms/op
Iteration   3: 5.226 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.430 ±(99.9%) 4.491 ms/op [Average]
  (min, avg, max) = (5.226, 5.430, 5.703), stdev = 0.246
  CI (99.9%): [0.939, 9.921] (assumes normal distribution)


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
# Warmup Iteration   1: 19.937 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.599 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.267 ±(99.9%) 0.013 ms/op
Iteration   1: 6.149 ±(99.9%) 0.011 ms/op
Iteration   2: 6.362 ±(99.9%) 0.014 ms/op
Iteration   3: 6.316 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.276 ±(99.9%) 2.042 ms/op [Average]
  (min, avg, max) = (6.149, 6.276, 6.362), stdev = 0.112
  CI (99.9%): [4.234, 8.318] (assumes normal distribution)


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
# Warmup Iteration   1: 17.128 ±(99.9%) 0.360 ms/op
# Warmup Iteration   2: 7.274 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.035 ±(99.9%) 0.027 ms/op
Iteration   1: 5.293 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.528 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 5.487 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 28.037 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 5.650 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  27.468 ms/op
                 createUser·p0.9999: 33.030 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175448
  mean =      5.473 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 76195 
    [ 5.000,  7.500) = 89002 
    [ 7.500, 10.000) = 8375 
    [10.000, 12.500) = 1173 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     31.505 ms/op
     p(99.9990) =     33.628 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.468 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.453 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.383 ±(99.9%) 0.017 ms/op
Iteration   1: 5.201 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  20.497 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 5.461 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   11.551 ms/op
                 existUser·p0.999:  23.852 ms/op
                 existUser·p0.9999: 29.922 ms/op
                 existUser·p1.00:   30.573 ms/op

Iteration   3: 5.383 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  18.433 ms/op
                 existUser·p0.9999: 27.867 ms/op
                 existUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179473
  mean =      5.346 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 86551 
    [ 5.000,  7.500) = 83962 
    [ 7.500, 10.000) = 6860 
    [10.000, 12.500) = 1227 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     28.612 ms/op
     p(99.9990) =     30.494 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.633 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 6.492 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.028 ms/op
Iteration   1: 5.550 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  23.815 ms/op
                 getUser·p0.9999: 28.708 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 5.486 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.840 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  15.745 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 5.300 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  26.812 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176347
  mean =      5.443 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 77943 
    [ 5.000,  7.500) = 88957 
    [ 7.500, 10.000) = 7189 
    [10.000, 12.500) = 1546 
    [12.500, 15.000) = 418 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     18.077 ms/op
     p(99.9900) =     29.256 ms/op
     p(99.9990) =     30.407 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 19.504 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 7.443 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.549 ±(99.9%) 0.026 ms/op
Iteration   1: 6.583 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.228 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  30.389 ms/op
                 listUser·p0.9999: 34.172 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 6.112 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   12.031 ms/op
                 listUser·p0.999:  27.934 ms/op
                 listUser·p0.9999: 31.952 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   3: 6.360 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.158 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.873 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  24.412 ms/op
                 listUser·p0.9999: 29.874 ms/op
                 listUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151202
  mean =      6.346 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 16944 
    [ 5.000,  7.500) = 114228 
    [ 7.500, 10.000) = 15516 
    [10.000, 12.500) = 2908 
    [12.500, 15.000) = 924 
    [15.000, 17.500) = 240 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.922 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     27.650 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     35.027 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.769 ± 4.038  ops/ms
ClientPb.existUser                       thrpt       3   6.134 ± 0.394  ops/ms
ClientPb.getUser                         thrpt       3   5.767 ± 2.176  ops/ms
ClientPb.listUser                        thrpt       3   5.034 ± 1.403  ops/ms
ClientPb.createUser                       avgt       3   5.378 ± 0.283   ms/op
ClientPb.existUser                        avgt       3   5.230 ± 3.430   ms/op
ClientPb.getUser                          avgt       3   5.430 ± 4.491   ms/op
ClientPb.listUser                         avgt       3   6.276 ± 2.042   ms/op
ClientPb.createUser                     sample  175448   5.473 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.684           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.505           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  179473   5.346 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.659           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.338           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.087           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.612           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.573           ms/op
ClientPb.getUser                        sample  176347   5.443 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.136           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.077           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.256           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  151202   6.346 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.095           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.922           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.063           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
