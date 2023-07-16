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
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 4.963 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 9.048 ops/ms
Iteration   2: 9.324 ops/ms
Iteration   3: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.280 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (9.048, 9.280, 9.469), stdev = 0.214
  CI (99.9%): [5.377, 13.183] (assumes normal distribution)


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
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 8.996 ops/ms
# Warmup Iteration   3: 9.747 ops/ms
Iteration   1: 9.955 ops/ms
Iteration   2: 9.850 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.902 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (9.850, 9.902, 9.955), stdev = 0.053
  CI (99.9%): [8.943, 10.862] (assumes normal distribution)


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
# Warmup Iteration   1: 3.129 ops/ms
# Warmup Iteration   2: 8.238 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.686 ops/ms
Iteration   2: 9.466 ops/ms
Iteration   3: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.530 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (9.438, 9.530, 9.686), stdev = 0.136
  CI (99.9%): [7.054, 12.006] (assumes normal distribution)


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
# Warmup Iteration   1: 2.704 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 7.884 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 7.994 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.967 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (7.906, 7.967, 8.000), stdev = 0.052
  CI (99.9%): [7.009, 8.924] (assumes normal distribution)


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
# Warmup Iteration   1: 8.550 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.606 ±(99.9%) 0.004 ms/op
Iteration   2: 3.403 ±(99.9%) 0.005 ms/op
Iteration   3: 3.394 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.468 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (3.394, 3.468, 3.606), stdev = 0.120
  CI (99.9%): [1.285, 5.651] (assumes normal distribution)


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
# Warmup Iteration   1: 8.625 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.010 ms/op
Iteration   2: 3.388 ±(99.9%) 0.005 ms/op
Iteration   3: 3.368 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 1.833 ms/op [Average]
  (min, avg, max) = (3.205, 3.320, 3.388), stdev = 0.100
  CI (99.9%): [1.487, 5.153] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.747 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.008 ms/op
Iteration   1: 3.373 ±(99.9%) 0.010 ms/op
Iteration   2: 3.372 ±(99.9%) 0.011 ms/op
Iteration   3: 3.395 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.372, 3.380, 3.395), stdev = 0.013
  CI (99.9%): [3.146, 3.614] (assumes normal distribution)


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
# Warmup Iteration   1: 10.128 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.006 ms/op
Iteration   1: 3.995 ±(99.9%) 0.012 ms/op
Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.993 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (3.986, 3.993, 3.999), stdev = 0.006
  CI (99.9%): [3.879, 4.107] (assumes normal distribution)


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
# Warmup Iteration   1: 8.652 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  19.795 ms/op
                 createUser·p0.9999: 22.866 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   2: 3.471 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  21.603 ms/op
                 createUser·p0.9999: 24.831 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.174 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 25.660 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273813
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8110 
    [ 2.500,  5.000) = 257003 
    [ 5.000,  7.500) = 7581 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.502 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 7.774 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.527 ms/op
                 existUser·p0.999:  18.606 ms/op
                 existUser·p0.9999: 22.633 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.655 ms/op
                 existUser·p0.999:  22.462 ms/op
                 existUser·p0.9999: 29.733 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 3.422 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  9.004 ms/op
                 existUser·p0.9999: 23.210 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286106
  mean =      3.352 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20519 
    [ 2.500,  5.000) = 260037 
    [ 5.000,  7.500) = 4620 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     11.991 ms/op
     p(99.9900) =     28.512 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 8.486 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.012 ms/op
Iteration   1: 3.571 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  20.034 ms/op
                 getUser·p0.9999: 22.284 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  22.479 ms/op
                 getUser·p0.9999: 25.749 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  19.939 ms/op
                 getUser·p0.9999: 26.147 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272086
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10558 
    [ 2.500,  5.000) = 252474 
    [ 5.000,  7.500) = 8017 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     25.421 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 9.845 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
Iteration   1: 3.844 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.609 ms/op
                 listUser·p0.999:  17.163 ms/op
                 listUser·p0.9999: 22.939 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.084 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.588 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 15.892 ms/op
                 listUser·p1.00:   16.548 ms/op

Iteration   3: 3.935 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 19.558 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242771
  mean =      3.952 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 234306 
    [ 5.000,  7.500) = 6292 
    [ 7.500, 10.000) = 1398 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     21.749 ms/op
     p(99.9990) =     23.701 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.280 ± 3.903  ops/ms
ClientPb.existUser                       thrpt       3   9.902 ± 0.959  ops/ms
ClientPb.getUser                         thrpt       3   9.530 ± 2.476  ops/ms
ClientPb.listUser                        thrpt       3   7.967 ± 0.958  ops/ms
ClientPb.createUser                       avgt       3   3.468 ± 2.183   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 1.833   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.234   ms/op
ClientPb.listUser                         avgt       3   3.993 ± 0.114   ms/op
ClientPb.createUser                     sample  273813   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.773           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.623           ms/op
ClientPb.existUser                      sample  286106   3.352 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.991           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  272086   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.600           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.421           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.542           ms/op
ClientPb.listUser                       sample  242771   3.952 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.795           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.749           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888           ms/op
