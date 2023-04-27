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
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 3.830 ops/ms
# Warmup Iteration   3: 7.568 ops/ms
Iteration   1: 7.751 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.167 ±(99.9%) 6.605 ops/ms [Average]
  (min, avg, max) = (7.751, 8.167, 8.413), stdev = 0.362
  CI (99.9%): [1.562, 14.772] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 6.713 ops/ms
# Warmup Iteration   3: 8.315 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.402 ops/ms
Iteration   3: 8.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.528 ±(99.9%) 4.059 ops/ms [Average]
  (min, avg, max) = (8.398, 8.528, 8.785), stdev = 0.222
  CI (99.9%): [4.469, 12.587] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.466 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.245 ±(99.9%) 3.827 ops/ms [Average]
  (min, avg, max) = (8.009, 8.245, 8.412), stdev = 0.210
  CI (99.9%): [4.418, 12.072] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.191 ops/ms
# Warmup Iteration   2: 6.144 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 6.897 ops/ms
Iteration   2: 6.721 ops/ms
Iteration   3: 7.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.948 ±(99.9%) 4.677 ops/ms [Average]
  (min, avg, max) = (6.721, 6.948, 7.226), stdev = 0.256
  CI (99.9%): [2.271, 11.625] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 10.953 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
Iteration   1: 3.904 ±(99.9%) 0.007 ms/op
Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
Iteration   3: 3.629 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.794 ±(99.9%) 2.649 ms/op [Average]
  (min, avg, max) = (3.629, 3.794, 3.904), stdev = 0.145
  CI (99.9%): [1.145, 6.443] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.229 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.003 ms/op
Iteration   1: 3.491 ±(99.9%) 0.003 ms/op
Iteration   2: 3.619 ±(99.9%) 0.006 ms/op
Iteration   3: 3.350 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.487 ±(99.9%) 2.447 ms/op [Average]
  (min, avg, max) = (3.350, 3.487, 3.619), stdev = 0.134
  CI (99.9%): [1.040, 5.933] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.655 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.006 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
Iteration   2: 3.485 ±(99.9%) 0.006 ms/op
Iteration   3: 3.383 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.429 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.383, 3.429, 3.485), stdev = 0.052
  CI (99.9%): [2.483, 4.374] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.266 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.009 ms/op
Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
Iteration   2: 4.248 ±(99.9%) 0.005 ms/op
Iteration   3: 4.215 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.203 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (4.145, 4.203, 4.248), stdev = 0.052
  CI (99.9%): [3.249, 5.156] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.249 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.013 ms/op
Iteration   1: 4.195 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.995 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   7.070 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  23.093 ms/op
                 createUser·p0.9999: 32.637 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   2: 3.899 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  11.961 ms/op
                 createUser·p0.9999: 30.173 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   3: 3.791 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.269 ms/op
                 createUser·p0.999:  28.786 ms/op
                 createUser·p0.9999: 41.653 ms/op
                 createUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242500
  mean =      3.955 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 227118 
    [ 5.000, 10.000) = 14775 
    [10.000, 15.000) = 320 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     42.074 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.048 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
Iteration   1: 3.704 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.839 ms/op
                 existUser·p0.999:  22.301 ms/op
                 existUser·p0.9999: 26.980 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 3.516 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 29.393 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 28.994 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 269163
  mean =      3.566 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6275 
    [ 2.500,  5.000) = 255927 
    [ 5.000,  7.500) = 5976 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 107 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     15.105 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 9.599 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
Iteration   1: 3.604 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.915 ms/op
                 getUser·p0.9999: 26.157 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 3.569 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  22.393 ms/op
                 getUser·p0.9999: 34.996 ms/op
                 getUser·p1.00:   36.241 ms/op

Iteration   3: 3.673 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  20.382 ms/op
                 getUser·p0.9999: 31.332 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265374
  mean =      3.615 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4899 
    [ 2.500,  5.000) = 250489 
    [ 5.000,  7.500) = 8758 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.564 ms/op
     p(99.9000) =     20.894 ms/op
     p(99.9900) =     33.504 ms/op
     p(99.9990) =     36.004 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 12.908 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.014 ms/op
Iteration   1: 4.342 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.190 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 29.722 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 4.167 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.312 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.487 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  18.033 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 221714
  mean =      4.328 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 206061 
    [ 5.000,  7.500) = 12608 
    [ 7.500, 10.000) = 2141 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     27.585 ms/op
     p(99.9990) =     29.961 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.167 ± 6.605  ops/ms
ClientPb.existUser                       thrpt       3   8.528 ± 4.059  ops/ms
ClientPb.getUser                         thrpt       3   8.245 ± 3.827  ops/ms
ClientPb.listUser                        thrpt       3   6.948 ± 4.677  ops/ms
ClientPb.createUser                       avgt       3   3.794 ± 2.649   ms/op
ClientPb.existUser                        avgt       3   3.487 ± 2.447   ms/op
ClientPb.getUser                          avgt       3   3.429 ± 0.945   ms/op
ClientPb.listUser                         avgt       3   4.203 ± 0.954   ms/op
ClientPb.createUser                     sample  242500   3.955 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.905           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.336           ms/op
ClientPb.existUser                      sample  269163   3.566 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  265374   3.615 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.564           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.894           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.504           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.241           ms/op
ClientPb.listUser                       sample  221714   4.328 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.190           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.645           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.585           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
