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
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 5.991 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 9.442 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.514 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (9.335, 9.514, 9.764), stdev = 0.223
  CI (99.9%): [5.439, 13.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 9.545 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.730 ±(99.9%) 0.546 ops/ms [Average]
  (min, avg, max) = (9.707, 9.730, 9.764), stdev = 0.030
  CI (99.9%): [9.183, 10.276] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.467 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.497 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (9.432, 9.497, 9.595), stdev = 0.087
  CI (99.9%): [7.919, 11.075] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.709 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.844 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.989 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (7.890, 7.989, 8.070), stdev = 0.091
  CI (99.9%): [6.327, 9.651] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.242 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.004 ms/op
Iteration   1: 3.317 ±(99.9%) 0.008 ms/op
Iteration   2: 3.489 ±(99.9%) 0.006 ms/op
Iteration   3: 3.446 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (3.317, 3.418, 3.489), stdev = 0.090
  CI (99.9%): [1.783, 5.052] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.224 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.006 ms/op
Iteration   1: 3.331 ±(99.9%) 0.006 ms/op
Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
Iteration   3: 3.131 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.223 ±(99.9%) 1.844 ms/op [Average]
  (min, avg, max) = (3.131, 3.223, 3.331), stdev = 0.101
  CI (99.9%): [1.379, 5.067] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.811 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.003 ms/op
Iteration   1: 3.499 ±(99.9%) 0.004 ms/op
Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
Iteration   3: 3.361 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.361, 3.413, 3.499), stdev = 0.075
  CI (99.9%): [2.044, 4.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.470 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.895 ±(99.9%) 0.013 ms/op
Iteration   2: 3.914 ±(99.9%) 0.014 ms/op
Iteration   3: 3.977 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.929 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.895, 3.929, 3.977), stdev = 0.043
  CI (99.9%): [3.143, 4.714] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.801 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.347 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.724 ms/op
                 createUser·p0.9999: 22.752 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  22.002 ms/op
                 createUser·p0.9999: 31.023 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   3: 3.553 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278187
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10527 
    [ 2.500,  5.000) = 261906 
    [ 5.000,  7.500) = 4859 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.361 ms/op
     p(99.9900) =     30.039 ms/op
     p(99.9990) =     31.956 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.804 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.007 ms/op
Iteration   1: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  19.094 ms/op
                 existUser·p0.9999: 26.129 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.680 ms/op
                 existUser·p0.999:  13.117 ms/op
                 existUser·p0.9999: 24.125 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  17.393 ms/op
                 existUser·p0.9999: 26.430 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285706
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15200 
    [ 2.500,  5.000) = 264388 
    [ 5.000,  7.500) = 5038 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     25.634 ms/op
     p(99.9990) =     26.912 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 9.032 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.012 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.929 ms/op
                 getUser·p0.999:  17.701 ms/op
                 getUser·p0.9999: 21.078 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 24.302 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  17.716 ms/op
                 getUser·p0.9999: 25.845 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279754
  mean =      3.431 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7578 
    [ 2.500,  5.000) = 265554 
    [ 5.000,  7.500) = 5487 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     24.677 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 10.467 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.013 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.666 ms/op
                 listUser·p0.9999: 23.600 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   8.043 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.974 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 15.679 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240898
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 233677 
    [ 5.000,  7.500) = 4881 
    [ 7.500, 10.000) = 1472 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     24.563 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.514 ± 4.075  ops/ms
ClientPb.existUser                       thrpt       3   9.730 ± 0.546  ops/ms
ClientPb.getUser                         thrpt       3   9.497 ± 1.578  ops/ms
ClientPb.listUser                        thrpt       3   7.989 ± 1.662  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 1.635   ms/op
ClientPb.existUser                        avgt       3   3.223 ± 1.844   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 1.370   ms/op
ClientPb.listUser                         avgt       3   3.929 ± 0.786   ms/op
ClientPb.createUser                     sample  278187   3.449 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.772           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.361           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.039           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  285706   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.269           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.634           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  279754   3.431 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.100           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.214           ms/op
ClientPb.listUser                       sample  240898   3.983 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
