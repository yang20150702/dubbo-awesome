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
# Warmup Iteration   1: 1.941 ops/ms
# Warmup Iteration   2: 5.165 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 9.147 ops/ms
Iteration   2: 9.051 ops/ms
Iteration   3: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.088 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (9.051, 9.088, 9.147), stdev = 0.051
  CI (99.9%): [8.153, 10.024] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 8.833 ops/ms
# Warmup Iteration   3: 9.198 ops/ms
Iteration   1: 9.433 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.535 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (9.433, 9.535, 9.684), stdev = 0.132
  CI (99.9%): [7.122, 11.947] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 7.987 ops/ms
# Warmup Iteration   3: 8.745 ops/ms
Iteration   1: 8.875 ops/ms
Iteration   2: 8.952 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.109 ±(99.9%) 6.227 ops/ms [Average]
  (min, avg, max) = (8.875, 9.109, 9.501), stdev = 0.341
  CI (99.9%): [2.882, 15.336] (assumes normal distribution)


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
# Warmup Iteration   1: 2.877 ops/ms
# Warmup Iteration   2: 7.361 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 7.774 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.986 ±(99.9%) 3.886 ops/ms [Average]
  (min, avg, max) = (7.774, 7.986, 8.200), stdev = 0.213
  CI (99.9%): [4.100, 11.872] (assumes normal distribution)


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
# Warmup Iteration   1: 9.836 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.008 ms/op
Iteration   1: 3.455 ±(99.9%) 0.006 ms/op
Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
Iteration   3: 3.548 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.469 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.403, 3.469, 3.548), stdev = 0.074
  CI (99.9%): [2.122, 4.815] (assumes normal distribution)


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
# Warmup Iteration   1: 9.354 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.006 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
Iteration   2: 3.489 ±(99.9%) 0.008 ms/op
Iteration   3: 3.359 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 1.924 ms/op [Average]
  (min, avg, max) = (3.280, 3.376, 3.489), stdev = 0.105
  CI (99.9%): [1.452, 5.300] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.062 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.004 ms/op
Iteration   1: 3.598 ±(99.9%) 0.006 ms/op
Iteration   2: 3.540 ±(99.9%) 0.010 ms/op
Iteration   3: 3.538 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.559 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.538, 3.559, 3.598), stdev = 0.034
  CI (99.9%): [2.939, 4.179] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.962 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.964 ±(99.9%) 0.010 ms/op
Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
Iteration   3: 3.985 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.994 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.964, 3.994, 4.033), stdev = 0.036
  CI (99.9%): [3.342, 4.646] (assumes normal distribution)


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
# Warmup Iteration   1: 8.531 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
Iteration   1: 3.453 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  20.837 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  23.259 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.512 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 25.851 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273755
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6868 
    [ 2.500,  5.000) = 260674 
    [ 5.000,  7.500) = 5237 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 168 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     25.252 ms/op
     p(99.9990) =     27.520 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 9.617 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.672 ms/op
                 existUser·p0.9999: 28.516 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.305 ms/op
                 existUser·p0.999:  17.153 ms/op
                 existUser·p0.9999: 25.090 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  20.511 ms/op
                 existUser·p0.9999: 27.612 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287457
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11765 
    [ 2.500,  5.000) = 271703 
    [ 5.000,  7.500) = 3243 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     19.580 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     28.881 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 9.000 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.012 ms/op
Iteration   1: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 36.499 ms/op
                 getUser·p1.00:   37.945 ms/op

Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.130 ms/op
                 getUser·p0.999:  22.998 ms/op
                 getUser·p0.9999: 30.512 ms/op
                 getUser·p1.00:   31.392 ms/op

Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  22.190 ms/op
                 getUser·p0.9999: 25.881 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270811
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4322 
    [ 2.500,  5.000) = 258427 
    [ 5.000,  7.500) = 6471 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     18.487 ms/op
     p(99.9900) =     35.035 ms/op
     p(99.9990) =     37.768 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 10.607 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.012 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  21.594 ms/op
                 listUser·p0.9999: 29.210 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   2: 4.177 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 18.385 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.023 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  16.704 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234488
  mean =      4.089 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 225442 
    [ 5.000,  7.500) = 6741 
    [ 7.500, 10.000) = 1405 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     28.023 ms/op
     p(99.9990) =     30.377 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.088 ± 0.935  ops/ms
ClientPb.existUser                       thrpt       3   9.535 ± 2.412  ops/ms
ClientPb.getUser                         thrpt       3   9.109 ± 6.227  ops/ms
ClientPb.listUser                        thrpt       3   7.986 ± 3.886  ops/ms
ClientPb.createUser                       avgt       3   3.469 ± 1.347   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 1.924   ms/op
ClientPb.getUser                          avgt       3   3.559 ± 0.620   ms/op
ClientPb.listUser                         avgt       3   3.994 ± 0.652   ms/op
ClientPb.createUser                     sample  273755   3.503 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.169           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.252           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.853           ms/op
ClientPb.existUser                      sample  287457   3.341 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.497           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.580           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.853           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  270811   3.543 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.604           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.487           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.035           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.945           ms/op
ClientPb.listUser                       sample  234488   4.089 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.023           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.835           ms/op
