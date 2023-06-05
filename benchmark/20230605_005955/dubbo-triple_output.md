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
# Warmup Iteration   1: 1.349 ops/ms
# Warmup Iteration   2: 3.326 ops/ms
# Warmup Iteration   3: 6.226 ops/ms
Iteration   1: 6.447 ops/ms
Iteration   2: 6.793 ops/ms
Iteration   3: 6.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.671 ±(99.9%) 3.545 ops/ms [Average]
  (min, avg, max) = (6.447, 6.671, 6.793), stdev = 0.194
  CI (99.9%): [3.126, 10.217] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 6.000 ops/ms
# Warmup Iteration   3: 7.037 ops/ms
Iteration   1: 6.858 ops/ms
Iteration   2: 6.964 ops/ms
Iteration   3: 7.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.011 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (6.858, 7.011, 7.211), stdev = 0.181
  CI (99.9%): [3.701, 10.322] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 6.222 ops/ms
# Warmup Iteration   3: 6.872 ops/ms
Iteration   1: 6.995 ops/ms
Iteration   2: 6.851 ops/ms
Iteration   3: 7.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.958 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (6.851, 6.958, 7.027), stdev = 0.093
  CI (99.9%): [5.255, 8.661] (assumes normal distribution)


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
# Warmup Iteration   1: 1.880 ops/ms
# Warmup Iteration   2: 4.984 ops/ms
# Warmup Iteration   3: 5.864 ops/ms
Iteration   1: 6.163 ops/ms
Iteration   2: 6.168 ops/ms
Iteration   3: 6.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.204 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (6.163, 6.204, 6.281), stdev = 0.066
  CI (99.9%): [4.995, 7.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.427 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.861 ±(99.9%) 0.009 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
Iteration   2: 4.680 ±(99.9%) 0.013 ms/op
Iteration   3: 4.655 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.664 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (4.655, 4.664, 4.680), stdev = 0.013
  CI (99.9%): [4.418, 4.910] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 14.689 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.562 ±(99.9%) 0.009 ms/op
Iteration   1: 4.561 ±(99.9%) 0.014 ms/op
Iteration   2: 4.536 ±(99.9%) 0.009 ms/op
Iteration   3: 4.507 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.535 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (4.507, 4.535, 4.561), stdev = 0.027
  CI (99.9%): [4.040, 5.030] (assumes normal distribution)


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
# Warmup Iteration   1: 13.915 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.262 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.007 ms/op
Iteration   1: 4.596 ±(99.9%) 0.009 ms/op
Iteration   2: 4.398 ±(99.9%) 0.017 ms/op
Iteration   3: 4.432 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.475 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (4.398, 4.475, 4.596), stdev = 0.106
  CI (99.9%): [2.545, 6.406] (assumes normal distribution)


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
# Warmup Iteration   1: 15.172 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.564 ±(99.9%) 0.008 ms/op
Iteration   1: 5.314 ±(99.9%) 0.014 ms/op
Iteration   2: 5.459 ±(99.9%) 0.013 ms/op
Iteration   3: 5.295 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.356 ±(99.9%) 1.631 ms/op [Average]
  (min, avg, max) = (5.295, 5.356, 5.459), stdev = 0.089
  CI (99.9%): [3.725, 6.988] (assumes normal distribution)


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
# Warmup Iteration   1: 13.923 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.919 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.027 ms/op
Iteration   1: 4.632 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 29.072 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 4.542 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  13.107 ms/op
                 createUser·p0.9999: 25.820 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 4.818 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  16.986 ms/op
                 createUser·p0.9999: 30.245 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 205809
  mean =      4.661 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 157841 
    [ 5.000,  7.500) = 42753 
    [ 7.500, 10.000) = 3907 
    [10.000, 12.500) = 711 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     16.410 ms/op
     p(99.9900) =     29.636 ms/op
     p(99.9990) =     30.436 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 14.163 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.577 ±(99.9%) 0.014 ms/op
Iteration   1: 4.587 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   6.283 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  14.668 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 4.571 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  18.809 ms/op
                 existUser·p0.9999: 39.584 ms/op
                 existUser·p1.00:   39.911 ms/op

Iteration   3: 4.494 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  17.414 ms/op
                 existUser·p0.9999: 29.974 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 210990
  mean =      4.550 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176 
    [ 2.500,  5.000) = 174259 
    [ 5.000,  7.500) = 31681 
    [ 7.500, 10.000) = 3756 
    [10.000, 12.500) = 738 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     17.335 ms/op
     p(99.9900) =     37.408 ms/op
     p(99.9990) =     39.904 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 13.817 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.613 ±(99.9%) 0.015 ms/op
Iteration   1: 4.642 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.701 ms/op
                 getUser·p0.99:   10.800 ms/op
                 getUser·p0.999:  19.075 ms/op
                 getUser·p0.9999: 23.203 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 4.470 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.436 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   8.872 ms/op
                 getUser·p0.999:  16.000 ms/op
                 getUser·p0.9999: 25.484 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 4.683 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.058 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.742 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  24.011 ms/op
                 getUser·p0.9999: 45.335 ms/op
                 getUser·p1.00:   46.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 208574
  mean =      4.597 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 170471 
    [ 5.000, 10.000) = 36160 
    [10.000, 15.000) = 1541 
    [15.000, 20.000) = 181 
    [20.000, 25.000) = 157 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     20.822 ms/op
     p(99.9900) =     42.214 ms/op
     p(99.9990) =     46.454 ms/op
     p(99.9999) =     46.531 ms/op
    p(100.0000) =     46.531 ms/op


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
# Warmup Iteration   1: 15.643 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.982 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.557 ±(99.9%) 0.022 ms/op
Iteration   1: 5.266 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 25.456 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 5.227 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  22.864 ms/op
                 listUser·p0.9999: 26.604 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 5.405 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.311 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  22.591 ms/op
                 listUser·p0.9999: 26.528 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 181009
  mean =      5.299 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 85202 
    [ 5.000,  7.500) = 88273 
    [ 7.500, 10.000) = 5522 
    [10.000, 12.500) = 1244 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     26.211 ms/op
     p(99.9990) =     27.782 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.671 ± 3.545  ops/ms
ClientPb.existUser                       thrpt       3   7.011 ± 3.310  ops/ms
ClientPb.getUser                         thrpt       3   6.958 ± 1.703  ops/ms
ClientPb.listUser                        thrpt       3   6.204 ± 1.209  ops/ms
ClientPb.createUser                       avgt       3   4.664 ± 0.246   ms/op
ClientPb.existUser                        avgt       3   4.535 ± 0.495   ms/op
ClientPb.getUser                          avgt       3   4.475 ± 1.930   ms/op
ClientPb.listUser                         avgt       3   5.356 ± 1.631   ms/op
ClientPb.createUser                     sample  205809   4.661 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.504           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.410           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.636           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.933           ms/op
ClientPb.existUser                      sample  210990   4.550 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.415           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.011           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.408           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.911           ms/op
ClientPb.getUser                        sample  208574   4.597 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.436           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.531           ms/op
ClientPb.listUser                       sample  181009   5.299 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.544           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.211           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
