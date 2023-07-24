# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.636 ops/ms
# Warmup Iteration   2: 3.208 ops/ms
# Warmup Iteration   3: 6.562 ops/ms
Iteration   1: 7.489 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.728 ±(99.9%) 4.370 ops/ms [Average]
  (min, avg, max) = (7.489, 7.728, 7.968), stdev = 0.240
  CI (99.9%): [3.357, 12.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 6.969 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 8.378 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.406 ±(99.9%) 0.447 ops/ms [Average]
  (min, avg, max) = (8.378, 8.406, 8.424), stdev = 0.024
  CI (99.9%): [7.959, 8.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.291 ops/ms
# Warmup Iteration   3: 7.742 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.853 ±(99.9%) 5.703 ops/ms [Average]
  (min, avg, max) = (7.526, 7.853, 8.149), stdev = 0.313
  CI (99.9%): [2.150, 13.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 5.348 ops/ms
# Warmup Iteration   3: 6.673 ops/ms
Iteration   1: 6.549 ops/ms
Iteration   2: 6.595 ops/ms
Iteration   3: 6.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.656 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (6.549, 6.656, 6.825), stdev = 0.148
  CI (99.9%): [3.959, 9.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.591 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
Iteration   1: 3.870 ±(99.9%) 0.012 ms/op
Iteration   2: 3.897 ±(99.9%) 0.011 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.927 ±(99.9%) 1.393 ms/op [Average]
  (min, avg, max) = (3.870, 3.927, 4.014), stdev = 0.076
  CI (99.9%): [2.534, 5.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.695 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.816 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.004 ms/op
Iteration   1: 3.749 ±(99.9%) 0.011 ms/op
Iteration   2: 3.762 ±(99.9%) 0.007 ms/op
Iteration   3: 3.655 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.722 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.655, 3.722, 3.762), stdev = 0.058
  CI (99.9%): [2.656, 4.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.118 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.007 ms/op
Iteration   1: 4.244 ±(99.9%) 0.004 ms/op
Iteration   2: 4.176 ±(99.9%) 0.004 ms/op
Iteration   3: 4.048 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.156 ±(99.9%) 1.812 ms/op [Average]
  (min, avg, max) = (4.048, 4.156, 4.244), stdev = 0.099
  CI (99.9%): [2.344, 5.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.451 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.747 ±(99.9%) 0.009 ms/op
Iteration   1: 4.831 ±(99.9%) 0.005 ms/op
Iteration   2: 4.641 ±(99.9%) 0.014 ms/op
Iteration   3: 4.573 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.682 ±(99.9%) 2.443 ms/op [Average]
  (min, avg, max) = (4.573, 4.682, 4.831), stdev = 0.134
  CI (99.9%): [2.238, 7.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.926 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.446 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.019 ms/op
Iteration   1: 4.033 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  11.579 ms/op
                 createUser·p0.9999: 27.003 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   2: 3.975 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  25.854 ms/op
                 createUser·p0.9999: 28.474 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 4.123 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.299 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  28.865 ms/op
                 createUser·p0.9999: 32.416 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237323
  mean =      4.043 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 475 
    [ 2.500,  5.000) = 222245 
    [ 5.000,  7.500) = 11933 
    [ 7.500, 10.000) = 2035 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     24.720 ms/op
     p(99.9900) =     30.876 ms/op
     p(99.9990) =     32.765 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.750 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 23.842 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.774 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.007 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.727 ms/op
                 existUser·p0.999:  24.084 ms/op
                 existUser·p0.9999: 30.351 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 3.726 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254513
  mean =      3.767 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 296 
    [ 2.500,  5.000) = 247009 
    [ 5.000,  7.500) = 5856 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     29.214 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.943 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.015 ms/op
Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 24.742 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  25.196 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 30.507 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242398
  mean =      3.959 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 232292 
    [ 5.000,  7.500) = 7088 
    [ 7.500, 10.000) = 2102 
    [10.000, 12.500) = 493 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     29.468 ms/op
     p(99.9990) =     31.121 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.435 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.017 ms/op
Iteration   1: 4.679 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  20.432 ms/op
                 listUser·p0.9999: 25.660 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 4.798 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  20.134 ms/op
                 listUser·p0.9999: 27.711 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   3: 4.770 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 18.035 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202147
  mean =      4.749 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 166074 
    [ 5.000,  7.500) = 31388 
    [ 7.500, 10.000) = 3622 
    [10.000, 12.500) = 534 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     19.623 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     28.540 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.728 ± 4.370  ops/ms
ClientPb.existUser                       thrpt       3   8.406 ± 0.447  ops/ms
ClientPb.getUser                         thrpt       3   7.853 ± 5.703  ops/ms
ClientPb.listUser                        thrpt       3   6.656 ± 2.697  ops/ms
ClientPb.createUser                       avgt       3   3.927 ± 1.393   ms/op
ClientPb.existUser                        avgt       3   3.722 ± 1.066   ms/op
ClientPb.getUser                          avgt       3   4.156 ± 1.812   ms/op
ClientPb.listUser                         avgt       3   4.682 ± 2.443   ms/op
ClientPb.createUser                     sample  237323   4.043 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.373           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.720           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.876           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  254513   3.767 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.326           ms/op
ClientPb.getUser                        sample  242398   3.959 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.530           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.498           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  202147   4.749 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.446           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.623           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.051           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.738           ms/op
