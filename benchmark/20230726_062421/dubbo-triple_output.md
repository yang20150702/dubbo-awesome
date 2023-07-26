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
# Warmup Iteration   1: 1.048 ops/ms
# Warmup Iteration   2: 2.278 ops/ms
# Warmup Iteration   3: 4.704 ops/ms
Iteration   1: 5.354 ops/ms
Iteration   2: 5.662 ops/ms
Iteration   3: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.552 ±(99.9%) 3.142 ops/ms [Average]
  (min, avg, max) = (5.354, 5.552, 5.662), stdev = 0.172
  CI (99.9%): [2.410, 8.694] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 5.102 ops/ms
# Warmup Iteration   3: 5.857 ops/ms
Iteration   1: 5.968 ops/ms
Iteration   2: 6.148 ops/ms
Iteration   3: 6.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.091 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (5.968, 6.091, 6.158), stdev = 0.107
  CI (99.9%): [4.141, 8.042] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.551 ops/ms
# Warmup Iteration   2: 4.584 ops/ms
# Warmup Iteration   3: 5.762 ops/ms
Iteration   1: 5.732 ops/ms
Iteration   2: 5.444 ops/ms
Iteration   3: 5.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.677 ±(99.9%) 3.854 ops/ms [Average]
  (min, avg, max) = (5.444, 5.677, 5.856), stdev = 0.211
  CI (99.9%): [1.824, 9.531] (assumes normal distribution)


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
# Warmup Iteration   1: 1.312 ops/ms
# Warmup Iteration   2: 3.729 ops/ms
# Warmup Iteration   3: 4.810 ops/ms
Iteration   1: 4.774 ops/ms
Iteration   2: 4.948 ops/ms
Iteration   3: 5.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.932 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (4.774, 4.932, 5.074), stdev = 0.151
  CI (99.9%): [2.186, 7.679] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.772 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.910 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.035 ±(99.9%) 0.012 ms/op
Iteration   1: 5.743 ±(99.9%) 0.012 ms/op
Iteration   2: 5.772 ±(99.9%) 0.008 ms/op
Iteration   3: 5.740 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.752 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (5.740, 5.752, 5.772), stdev = 0.018
  CI (99.9%): [5.429, 6.075] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.144 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.321 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.415 ±(99.9%) 0.009 ms/op
Iteration   1: 5.333 ±(99.9%) 0.016 ms/op
Iteration   2: 5.235 ±(99.9%) 0.015 ms/op
Iteration   3: 5.250 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.273 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (5.235, 5.273, 5.333), stdev = 0.053
  CI (99.9%): [4.308, 6.237] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.804 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.621 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.921 ±(99.9%) 0.010 ms/op
Iteration   1: 5.838 ±(99.9%) 0.010 ms/op
Iteration   2: 5.693 ±(99.9%) 0.012 ms/op
Iteration   3: 5.578 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.703 ±(99.9%) 2.381 ms/op [Average]
  (min, avg, max) = (5.578, 5.703, 5.838), stdev = 0.131
  CI (99.9%): [3.322, 8.084] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.082 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 8.054 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.717 ±(99.9%) 0.016 ms/op
Iteration   1: 6.614 ±(99.9%) 0.012 ms/op
Iteration   2: 6.780 ±(99.9%) 0.016 ms/op
Iteration   3: 6.704 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.699 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (6.614, 6.699, 6.780), stdev = 0.083
  CI (99.9%): [5.182, 8.216] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.109 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.102 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.025 ms/op
Iteration   1: 5.507 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.671 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  26.004 ms/op
                 createUser·p0.9999: 29.006 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   2: 5.409 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.617 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  30.497 ms/op
                 createUser·p0.9999: 36.438 ms/op
                 createUser·p1.00:   37.159 ms/op

Iteration   3: 5.675 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.515 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  15.363 ms/op
                 createUser·p0.9999: 30.388 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173503
  mean =      5.528 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 54859 
    [ 5.000,  7.500) = 111476 
    [ 7.500, 10.000) = 5324 
    [10.000, 12.500) = 1093 
    [12.500, 15.000) = 402 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.515 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     35.344 ms/op
     p(99.9990) =     36.774 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.152 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.535 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.760 ±(99.9%) 0.023 ms/op
Iteration   1: 5.371 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.905 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  15.842 ms/op
                 existUser·p0.9999: 28.313 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 5.254 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.056 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   6.824 ms/op
                 existUser·p0.99:   9.503 ms/op
                 existUser·p0.999:  26.706 ms/op
                 existUser·p0.9999: 31.071 ms/op
                 existUser·p1.00:   33.194 ms/op

Iteration   3: 5.449 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.767 ms/op
                 existUser·p0.999:  29.166 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179175
  mean =      5.357 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 77682 
    [ 5.000,  7.500) = 92499 
    [ 7.500, 10.000) = 7149 
    [10.000, 12.500) = 1205 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.639 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.064 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.657 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.850 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.677 ±(99.9%) 0.018 ms/op
Iteration   1: 5.780 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   7.954 ms/op
                 getUser·p0.99:   10.600 ms/op
                 getUser·p0.999:  30.291 ms/op
                 getUser·p0.9999: 34.402 ms/op
                 getUser·p1.00:   38.339 ms/op

Iteration   2: 5.765 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  29.789 ms/op
                 getUser·p0.9999: 32.640 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 5.607 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.691 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.242 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  20.833 ms/op
                 getUser·p0.9999: 31.860 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167886
  mean =      5.716 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 38254 
    [ 5.000,  7.500) = 120086 
    [ 7.500, 10.000) = 6653 
    [10.000, 12.500) = 1977 
    [12.500, 15.000) = 474 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 100 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     28.086 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     36.203 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 21.237 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 8.195 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.632 ±(99.9%) 0.027 ms/op
Iteration   1: 6.746 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.986 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.149 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.827 ms/op
                 listUser·p0.999:  26.103 ms/op
                 listUser·p0.9999: 30.688 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   2: 6.587 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.514 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  26.622 ms/op
                 listUser·p0.9999: 35.324 ms/op
                 listUser·p1.00:   39.059 ms/op

Iteration   3: 6.586 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.849 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 36.072 ms/op
                 listUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144542
  mean =      6.639 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2817 
    [ 5.000,  7.500) = 123736 
    [ 7.500, 10.000) = 14053 
    [10.000, 12.500) = 2636 
    [12.500, 15.000) = 761 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      6.341 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     38.622 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.552 ± 3.142  ops/ms
ClientPb.existUser                       thrpt       3   6.091 ± 1.950  ops/ms
ClientPb.getUser                         thrpt       3   5.677 ± 3.854  ops/ms
ClientPb.listUser                        thrpt       3   4.932 ± 2.747  ops/ms
ClientPb.createUser                       avgt       3   5.752 ± 0.323   ms/op
ClientPb.existUser                        avgt       3   5.273 ± 0.965   ms/op
ClientPb.getUser                          avgt       3   5.703 ± 2.381   ms/op
ClientPb.listUser                         avgt       3   6.699 ± 1.517   ms/op
ClientPb.createUser                     sample  173503   5.528 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.644           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.142           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  179175   5.357 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.616           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.639           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  167886   5.716 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.191           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.092           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.339           ms/op
ClientPb.listUser                       sample  144542   6.639 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.341           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.444           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.324           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.059           ms/op
