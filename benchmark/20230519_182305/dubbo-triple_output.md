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
# Warmup Iteration   1: 2.070 ops/ms
# Warmup Iteration   2: 4.868 ops/ms
# Warmup Iteration   3: 8.669 ops/ms
Iteration   1: 9.175 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.253 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (9.154, 9.253, 9.430), stdev = 0.153
  CI (99.9%): [6.454, 12.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 8.769 ops/ms
# Warmup Iteration   3: 9.570 ops/ms
Iteration   1: 9.943 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.894 ±(99.9%) 2.876 ops/ms [Average]
  (min, avg, max) = (9.718, 9.894, 10.022), stdev = 0.158
  CI (99.9%): [7.018, 12.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.762 ops/ms
# Warmup Iteration   2: 7.873 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.205 ops/ms
Iteration   2: 9.310 ops/ms
Iteration   3: 9.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.253 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (9.205, 9.253, 9.310), stdev = 0.053
  CI (99.9%): [8.285, 10.220] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.664 ops/ms
# Warmup Iteration   2: 7.499 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.760 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.958 ±(99.9%) 3.428 ops/ms [Average]
  (min, avg, max) = (7.760, 7.958, 8.133), stdev = 0.188
  CI (99.9%): [4.531, 11.386] (assumes normal distribution)


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
# Warmup Iteration   1: 10.087 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.007 ms/op
Iteration   1: 3.490 ±(99.9%) 0.010 ms/op
Iteration   2: 3.374 ±(99.9%) 0.015 ms/op
Iteration   3: 3.282 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (3.282, 3.382, 3.490), stdev = 0.105
  CI (99.9%): [1.473, 5.291] (assumes normal distribution)


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
# Warmup Iteration   1: 8.597 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.008 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 2.471 ms/op [Average]
  (min, avg, max) = (3.184, 3.284, 3.439), stdev = 0.135
  CI (99.9%): [0.814, 5.755] (assumes normal distribution)


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
# Warmup Iteration   1: 10.212 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.008 ms/op
Iteration   1: 3.487 ±(99.9%) 0.008 ms/op
Iteration   2: 3.387 ±(99.9%) 0.008 ms/op
Iteration   3: 3.458 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.387, 3.444, 3.487), stdev = 0.052
  CI (99.9%): [2.502, 4.385] (assumes normal distribution)


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
# Warmup Iteration   1: 10.887 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
Iteration   1: 4.090 ±(99.9%) 0.012 ms/op
Iteration   2: 4.066 ±(99.9%) 0.008 ms/op
Iteration   3: 4.107 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.087 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (4.066, 4.087, 4.107), stdev = 0.021
  CI (99.9%): [3.712, 4.462] (assumes normal distribution)


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
# Warmup Iteration   1: 9.119 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
Iteration   1: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  19.440 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  22.413 ms/op
                 createUser·p0.9999: 38.011 ms/op
                 createUser·p1.00:   39.977 ms/op

Iteration   3: 3.506 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  18.047 ms/op
                 createUser·p0.9999: 23.851 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275111
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8090 
    [ 2.500,  5.000) = 260172 
    [ 5.000,  7.500) = 5702 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     18.379 ms/op
     p(99.9900) =     36.798 ms/op
     p(99.9990) =     39.420 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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
# Warmup Iteration   1: 9.175 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  19.702 ms/op
                 existUser·p0.9999: 22.791 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.370 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  20.197 ms/op
                 existUser·p0.9999: 25.050 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287944
  mean =      3.336 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22497 
    [ 2.500,  5.000) = 258817 
    [ 5.000,  7.500) = 5665 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     24.321 ms/op
     p(99.9990) =     25.550 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 8.988 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.013 ms/op
Iteration   1: 3.542 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  13.196 ms/op
                 getUser·p0.9999: 25.230 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  24.838 ms/op
                 getUser·p0.9999: 30.295 ms/op
                 getUser·p1.00:   31.818 ms/op

Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  22.443 ms/op
                 getUser·p0.9999: 37.935 ms/op
                 getUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276435
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 269985 
    [ 5.000, 10.000) = 6002 
    [10.000, 15.000) = 183 
    [15.000, 20.000) = 9 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.387 ms/op
     p(99.9000) =     13.989 ms/op
     p(99.9900) =     36.026 ms/op
     p(99.9990) =     40.174 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 11.077 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.013 ms/op
Iteration   1: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  17.655 ms/op
                 listUser·p0.9999: 23.990 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   9.515 ms/op
                 listUser·p0.999:  15.931 ms/op
                 listUser·p0.9999: 18.289 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.986 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.050 ms/op
                 listUser·p0.999:  14.886 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238571
  mean =      4.020 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 228311 
    [ 5.000,  7.500) = 7581 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     22.830 ms/op
     p(99.9990) =     25.512 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.253 ± 2.799  ops/ms
ClientPb.existUser                       thrpt       3   9.894 ± 2.876  ops/ms
ClientPb.getUser                         thrpt       3   9.253 ± 0.967  ops/ms
ClientPb.listUser                        thrpt       3   7.958 ± 3.428  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 1.909   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 2.471   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.941   ms/op
ClientPb.listUser                         avgt       3   4.087 ± 0.375   ms/op
ClientPb.createUser                     sample  275111   3.488 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.798           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.977           ms/op
ClientPb.existUser                      sample  287944   3.336 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.752           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.076           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.321           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.345           ms/op
ClientPb.getUser                        sample  276435   3.470 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.989           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.026           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.878           ms/op
ClientPb.listUser                       sample  238571   4.020 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.830           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
