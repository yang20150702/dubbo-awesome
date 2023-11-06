# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.657 ops/ms
# Warmup Iteration   2: 3.899 ops/ms
# Warmup Iteration   3: 7.253 ops/ms
Iteration   1: 7.702 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 7.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.920 ±(99.9%) 4.818 ops/ms [Average]
  (min, avg, max) = (7.702, 7.920, 8.213), stdev = 0.264
  CI (99.9%): [3.102, 12.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 7.191 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.624 ops/ms
Iteration   3: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.470 ±(99.9%) 3.217 ops/ms [Average]
  (min, avg, max) = (8.277, 8.470, 8.624), stdev = 0.176
  CI (99.9%): [5.253, 11.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.071 ±(99.9%) 4.642 ops/ms [Average]
  (min, avg, max) = (7.862, 8.071, 8.354), stdev = 0.254
  CI (99.9%): [3.429, 12.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 5.874 ops/ms
# Warmup Iteration   3: 6.698 ops/ms
Iteration   1: 6.769 ops/ms
Iteration   2: 7.026 ops/ms
Iteration   3: 6.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.849 ±(99.9%) 2.805 ops/ms [Average]
  (min, avg, max) = (6.752, 6.849, 7.026), stdev = 0.154
  CI (99.9%): [4.044, 9.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.152 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.005 ms/op
Iteration   1: 3.966 ±(99.9%) 0.005 ms/op
Iteration   2: 4.030 ±(99.9%) 0.005 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.004 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.966, 4.004, 4.030), stdev = 0.033
  CI (99.9%): [3.398, 4.610] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.929 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.003 ms/op
Iteration   1: 3.702 ±(99.9%) 0.006 ms/op
Iteration   2: 3.786 ±(99.9%) 0.004 ms/op
Iteration   3: 3.753 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.747 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (3.702, 3.747, 3.786), stdev = 0.042
  CI (99.9%): [2.981, 4.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.733 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.005 ms/op
Iteration   1: 4.082 ±(99.9%) 0.006 ms/op
Iteration   2: 4.096 ±(99.9%) 0.006 ms/op
Iteration   3: 4.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.089 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (4.082, 4.089, 4.096), stdev = 0.007
  CI (99.9%): [3.957, 4.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.622 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.008 ms/op
Iteration   1: 4.650 ±(99.9%) 0.013 ms/op
Iteration   2: 4.614 ±(99.9%) 0.012 ms/op
Iteration   3: 4.713 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.659 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (4.614, 4.659, 4.713), stdev = 0.050
  CI (99.9%): [3.747, 5.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.291 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.019 ms/op
Iteration   1: 4.098 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  23.323 ms/op
                 createUser·p0.9999: 26.417 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 4.013 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.029 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  15.070 ms/op
                 createUser·p0.9999: 29.132 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 4.191 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  28.457 ms/op
                 createUser·p0.9999: 30.355 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234143
  mean =      4.099 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 348 
    [ 2.500,  5.000) = 217409 
    [ 5.000,  7.500) = 13610 
    [ 7.500, 10.000) = 1943 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 112 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     23.490 ms/op
     p(99.9900) =     29.824 ms/op
     p(99.9990) =     30.583 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.422 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.791 ms/op
                 existUser·p0.999:  12.141 ms/op
                 existUser·p0.9999: 23.352 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.850 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  15.953 ms/op
                 existUser·p0.9999: 26.663 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   7.259 ms/op
                 existUser·p0.999:  24.072 ms/op
                 existUser·p0.9999: 26.354 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248656
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 557 
    [ 2.500,  5.000) = 238879 
    [ 5.000,  7.500) = 6865 
    [ 7.500, 10.000) = 1673 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.735 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.214 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.500 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.014 ms/op
Iteration   1: 4.248 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  24.137 ms/op
                 getUser·p0.9999: 43.218 ms/op
                 getUser·p1.00:   43.975 ms/op

Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  14.730 ms/op
                 getUser·p0.9999: 30.605 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 4.223 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  29.305 ms/op
                 getUser·p0.9999: 32.880 ms/op
                 getUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228161
  mean =      4.210 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 207737 
    [ 5.000, 10.000) = 19447 
    [10.000, 15.000) = 667 
    [15.000, 20.000) = 38 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 89 
    [30.000, 35.000) = 90 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     24.276 ms/op
     p(99.9900) =     41.615 ms/op
     p(99.9990) =     43.761 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.281 ±(99.9%) 0.363 ms/op
# Warmup Iteration   2: 5.562 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.019 ms/op
Iteration   1: 4.770 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 27.240 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 4.853 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  20.234 ms/op
                 listUser·p0.9999: 24.924 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   3: 4.663 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.488 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201570
  mean =      4.761 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 165142 
    [ 5.000,  7.500) = 31469 
    [ 7.500, 10.000) = 3445 
    [10.000, 12.500) = 790 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     26.396 ms/op
     p(99.9990) =     27.721 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.920 ± 4.818  ops/ms
ClientPb.existUser                       thrpt       3   8.470 ± 3.217  ops/ms
ClientPb.getUser                         thrpt       3   8.071 ± 4.642  ops/ms
ClientPb.listUser                        thrpt       3   6.849 ± 2.805  ops/ms
ClientPb.createUser                       avgt       3   4.004 ± 0.606   ms/op
ClientPb.existUser                        avgt       3   3.747 ± 0.766   ms/op
ClientPb.getUser                          avgt       3   4.089 ± 0.132   ms/op
ClientPb.listUser                         avgt       3   4.659 ± 0.912   ms/op
ClientPb.createUser                     sample  234143   4.099 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.548           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.490           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.824           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  248656   3.861 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.735           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  228161   4.210 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.475           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.276           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.975           ms/op
ClientPb.listUser                       sample  201570   4.761 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.366           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
