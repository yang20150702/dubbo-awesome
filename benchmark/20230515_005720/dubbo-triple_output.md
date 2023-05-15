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
# Warmup Iteration   1: 1.184 ops/ms
# Warmup Iteration   2: 2.787 ops/ms
# Warmup Iteration   3: 5.829 ops/ms
Iteration   1: 6.153 ops/ms
Iteration   2: 6.384 ops/ms
Iteration   3: 6.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.241 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (6.153, 6.241, 6.384), stdev = 0.125
  CI (99.9%): [3.956, 8.527] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 5.544 ops/ms
# Warmup Iteration   3: 6.559 ops/ms
Iteration   1: 6.861 ops/ms
Iteration   2: 6.548 ops/ms
Iteration   3: 6.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.720 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (6.548, 6.720, 6.861), stdev = 0.159
  CI (99.9%): [3.816, 9.624] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.836 ops/ms
# Warmup Iteration   2: 5.286 ops/ms
# Warmup Iteration   3: 6.250 ops/ms
Iteration   1: 6.484 ops/ms
Iteration   2: 6.081 ops/ms
Iteration   3: 6.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.309 ±(99.9%) 3.767 ops/ms [Average]
  (min, avg, max) = (6.081, 6.309, 6.484), stdev = 0.206
  CI (99.9%): [2.542, 10.076] (assumes normal distribution)


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
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 3.586 ops/ms
# Warmup Iteration   3: 5.126 ops/ms
Iteration   1: 5.158 ops/ms
Iteration   2: 5.316 ops/ms
Iteration   3: 5.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.357 ±(99.9%) 4.053 ops/ms [Average]
  (min, avg, max) = (5.158, 5.357, 5.597), stdev = 0.222
  CI (99.9%): [1.304, 9.409] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.407 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.611 ±(99.9%) 0.009 ms/op
Iteration   1: 5.173 ±(99.9%) 0.011 ms/op
Iteration   2: 5.179 ±(99.9%) 0.010 ms/op
Iteration   3: 5.236 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.196 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (5.173, 5.196, 5.236), stdev = 0.035
  CI (99.9%): [4.563, 5.830] (assumes normal distribution)


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
# Warmup Iteration   1: 15.838 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.693 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.010 ms/op
Iteration   1: 4.905 ±(99.9%) 0.015 ms/op
Iteration   2: 4.880 ±(99.9%) 0.010 ms/op
Iteration   3: 5.081 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.955 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (4.880, 4.955, 5.081), stdev = 0.109
  CI (99.9%): [2.962, 6.949] (assumes normal distribution)


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
# Warmup Iteration   1: 15.919 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.376 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.290 ±(99.9%) 0.010 ms/op
Iteration   1: 5.052 ±(99.9%) 0.014 ms/op
Iteration   2: 5.263 ±(99.9%) 0.014 ms/op
Iteration   3: 5.139 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.151 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (5.052, 5.151, 5.263), stdev = 0.106
  CI (99.9%): [3.221, 7.082] (assumes normal distribution)


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
# Warmup Iteration   1: 17.734 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.026 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.165 ±(99.9%) 0.017 ms/op
Iteration   1: 5.956 ±(99.9%) 0.014 ms/op
Iteration   2: 6.047 ±(99.9%) 0.010 ms/op
Iteration   3: 6.114 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.039 ±(99.9%) 1.440 ms/op [Average]
  (min, avg, max) = (5.956, 6.039, 6.114), stdev = 0.079
  CI (99.9%): [4.599, 7.480] (assumes normal distribution)


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
# Warmup Iteration   1: 17.222 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.909 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.021 ms/op
Iteration   1: 5.036 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.889 ms/op
                 createUser·p0.99:   10.322 ms/op
                 createUser·p0.999:  24.502 ms/op
                 createUser·p0.9999: 29.259 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   2: 5.102 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.119 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  26.182 ms/op
                 createUser·p0.9999: 31.014 ms/op
                 createUser·p1.00:   31.916 ms/op

Iteration   3: 4.926 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.431 ms/op
                 createUser·p0.99:   8.921 ms/op
                 createUser·p0.999:  18.929 ms/op
                 createUser·p0.9999: 29.737 ms/op
                 createUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 191070
  mean =      5.020 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 128209 
    [ 5.000,  7.500) = 56830 
    [ 7.500, 10.000) = 4276 
    [10.000, 12.500) = 1105 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     24.649 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     31.797 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 15.860 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 5.999 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.019 ms/op
Iteration   1: 5.086 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.545 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  22.497 ms/op
                 existUser·p0.9999: 26.776 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 4.877 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.653 ms/op
                 existUser·p0.90:   5.718 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  16.768 ms/op
                 existUser·p0.9999: 29.400 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   3: 4.937 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   5.857 ms/op
                 existUser·p0.95:   6.816 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  18.611 ms/op
                 existUser·p0.9999: 30.353 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193187
  mean =      4.965 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 131219 
    [ 5.000,  7.500) = 54372 
    [ 7.500, 10.000) = 5865 
    [10.000, 12.500) = 1125 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     19.425 ms/op
     p(99.9900) =     29.460 ms/op
     p(99.9990) =     31.822 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 19.019 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 6.931 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.021 ms/op
Iteration   1: 5.211 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.056 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.734 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  25.359 ms/op
                 getUser·p0.9999: 30.175 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   2: 5.428 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.949 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   7.045 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  13.667 ms/op
                 getUser·p0.9999: 27.729 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 5.260 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.732 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.853 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  28.236 ms/op
                 getUser·p0.9999: 39.431 ms/op
                 getUser·p1.00:   44.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181096
  mean =      5.298 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 91768 
    [ 5.000, 10.000) = 87240 
    [10.000, 15.000) = 1741 
    [15.000, 20.000) = 157 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     22.458 ms/op
     p(99.9900) =     35.513 ms/op
     p(99.9990) =     41.595 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


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
# Warmup Iteration   1: 19.006 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 7.197 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.202 ±(99.9%) 0.024 ms/op
Iteration   1: 6.056 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.505 ms/op
                 listUser·p0.999:  25.690 ms/op
                 listUser·p0.9999: 28.054 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 6.354 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  28.907 ms/op
                 listUser·p0.9999: 31.288 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 5.821 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   3.322 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  23.487 ms/op
                 listUser·p0.9999: 28.575 ms/op
                 listUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158185
  mean =      6.069 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 11985 
    [ 5.000,  7.500) = 133637 
    [ 7.500, 10.000) = 8951 
    [10.000, 12.500) = 2673 
    [12.500, 15.000) = 520 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      5.751 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     26.307 ms/op
     p(99.9900) =     30.939 ms/op
     p(99.9990) =     31.460 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.241 ± 2.285  ops/ms
ClientPb.existUser                       thrpt       3   6.720 ± 2.904  ops/ms
ClientPb.getUser                         thrpt       3   6.309 ± 3.767  ops/ms
ClientPb.listUser                        thrpt       3   5.357 ± 4.053  ops/ms
ClientPb.createUser                       avgt       3   5.196 ± 0.633   ms/op
ClientPb.existUser                        avgt       3   4.955 ± 1.993   ms/op
ClientPb.getUser                          avgt       3   5.151 ± 1.930   ms/op
ClientPb.listUser                         avgt       3   6.039 ± 1.440   ms/op
ClientPb.createUser                     sample  191070   5.020 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.750           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.781           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.649           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.343           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.916           ms/op
ClientPb.existUser                      sample  193187   4.965 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.425           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.460           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  181096   5.298 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.056           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.458           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.513           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.040           ms/op
ClientPb.listUser                       sample  158185   6.069 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.436           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.307           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.556           ms/op
