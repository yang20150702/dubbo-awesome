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
# Warmup Iteration   1: 1.023 ops/ms
# Warmup Iteration   2: 2.604 ops/ms
# Warmup Iteration   3: 5.542 ops/ms
Iteration   1: 5.603 ops/ms
Iteration   2: 5.981 ops/ms
Iteration   3: 6.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.926 ±(99.9%) 5.455 ops/ms [Average]
  (min, avg, max) = (5.603, 5.926, 6.193), stdev = 0.299
  CI (99.9%): [0.471, 11.380] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.723 ops/ms
# Warmup Iteration   2: 5.228 ops/ms
# Warmup Iteration   3: 6.852 ops/ms
Iteration   1: 6.639 ops/ms
Iteration   2: 6.832 ops/ms
Iteration   3: 6.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.636 ±(99.9%) 3.606 ops/ms [Average]
  (min, avg, max) = (6.437, 6.636, 6.832), stdev = 0.198
  CI (99.9%): [3.030, 10.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.644 ops/ms
# Warmup Iteration   2: 5.006 ops/ms
# Warmup Iteration   3: 6.164 ops/ms
Iteration   1: 6.170 ops/ms
Iteration   2: 6.234 ops/ms
Iteration   3: 6.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.181 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (6.138, 6.181, 6.234), stdev = 0.049
  CI (99.9%): [5.289, 7.072] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.260 ops/ms
# Warmup Iteration   2: 3.922 ops/ms
# Warmup Iteration   3: 4.888 ops/ms
Iteration   1: 4.903 ops/ms
Iteration   2: 4.964 ops/ms
Iteration   3: 5.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.987 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (4.903, 4.987, 5.095), stdev = 0.098
  CI (99.9%): [3.198, 6.777] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.891 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.457 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.854 ±(99.9%) 0.009 ms/op
Iteration   1: 5.773 ±(99.9%) 0.014 ms/op
Iteration   2: 5.388 ±(99.9%) 0.016 ms/op
Iteration   3: 5.484 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.549 ±(99.9%) 3.656 ms/op [Average]
  (min, avg, max) = (5.388, 5.549, 5.773), stdev = 0.200
  CI (99.9%): [1.893, 9.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.038 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.037 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.677 ±(99.9%) 0.006 ms/op
Iteration   1: 5.294 ±(99.9%) 0.008 ms/op
Iteration   2: 5.438 ±(99.9%) 0.015 ms/op
Iteration   3: 5.273 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.335 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (5.273, 5.335, 5.438), stdev = 0.090
  CI (99.9%): [3.698, 6.971] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.956 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.559 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.011 ms/op
Iteration   1: 5.520 ±(99.9%) 0.022 ms/op
Iteration   2: 5.386 ±(99.9%) 0.017 ms/op
Iteration   3: 5.226 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.377 ±(99.9%) 2.684 ms/op [Average]
  (min, avg, max) = (5.226, 5.377, 5.520), stdev = 0.147
  CI (99.9%): [2.693, 8.061] (assumes normal distribution)


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
# Warmup Iteration   1: 18.139 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.528 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.455 ±(99.9%) 0.017 ms/op
Iteration   1: 6.200 ±(99.9%) 0.016 ms/op
Iteration   2: 6.168 ±(99.9%) 0.021 ms/op
Iteration   3: 6.240 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.203 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (6.168, 6.203, 6.240), stdev = 0.036
  CI (99.9%): [5.551, 6.854] (assumes normal distribution)


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
# Warmup Iteration   1: 17.724 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 7.179 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.109 ±(99.9%) 0.029 ms/op
Iteration   1: 5.517 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  24.073 ms/op
                 createUser·p0.9999: 29.938 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   2: 5.417 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.687 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  25.657 ms/op
                 createUser·p0.9999: 29.412 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 5.489 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.389 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  26.157 ms/op
                 createUser·p0.9999: 30.415 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175133
  mean =      5.474 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 60954 
    [ 5.000,  7.500) = 104499 
    [ 7.500, 10.000) = 7520 
    [10.000, 12.500) = 1480 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.670 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     25.111 ms/op
     p(99.9900) =     30.031 ms/op
     p(99.9990) =     32.996 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 18.446 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.358 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.018 ms/op
Iteration   1: 5.203 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.642 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.255 ms/op
                 existUser·p0.999:  24.607 ms/op
                 existUser·p0.9999: 29.126 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   2: 5.067 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  14.073 ms/op
                 existUser·p0.9999: 32.899 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   3: 5.501 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   11.993 ms/op
                 existUser·p0.999:  26.239 ms/op
                 existUser·p0.9999: 29.088 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182711
  mean =      5.251 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 102149 
    [ 5.000,  7.500) = 70597 
    [ 7.500, 10.000) = 7433 
    [10.000, 12.500) = 1746 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     31.603 ms/op
     p(99.9990) =     33.495 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 19.590 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.280 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.023 ms/op
Iteration   1: 5.555 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.683 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   13.468 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 28.254 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 5.479 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   10.715 ms/op
                 getUser·p0.999:  23.941 ms/op
                 getUser·p0.9999: 38.404 ms/op
                 getUser·p1.00:   39.977 ms/op

Iteration   3: 5.427 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   3.092 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  28.610 ms/op
                 getUser·p0.9999: 34.493 ms/op
                 getUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174908
  mean =      5.486 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 70957 
    [ 5.000,  7.500) = 93644 
    [ 7.500, 10.000) = 6924 
    [10.000, 12.500) = 2079 
    [12.500, 15.000) = 659 
    [15.000, 17.500) = 323 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     24.972 ms/op
     p(99.9900) =     35.294 ms/op
     p(99.9990) =     38.848 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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
# Warmup Iteration   1: 20.548 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 7.693 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.171 ±(99.9%) 0.020 ms/op
Iteration   1: 6.160 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.449 ms/op
                 listUser·p0.999:  25.558 ms/op
                 listUser·p0.9999: 28.659 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 6.350 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.823 ms/op
                 listUser·p0.999:  27.412 ms/op
                 listUser·p0.9999: 33.356 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 6.541 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   11.933 ms/op
                 listUser·p0.999:  23.897 ms/op
                 listUser·p0.9999: 27.205 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151318
  mean =      6.347 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 6853 
    [ 5.000,  7.500) = 128421 
    [ 7.500, 10.000) = 11985 
    [10.000, 12.500) = 2932 
    [12.500, 15.000) = 612 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     25.450 ms/op
     p(99.9900) =     32.181 ms/op
     p(99.9990) =     33.914 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.926 ± 5.455  ops/ms
ClientPb.existUser                       thrpt       3   6.636 ± 3.606  ops/ms
ClientPb.getUser                         thrpt       3   6.181 ± 0.892  ops/ms
ClientPb.listUser                        thrpt       3   4.987 ± 1.790  ops/ms
ClientPb.createUser                       avgt       3   5.549 ± 3.656   ms/op
ClientPb.existUser                        avgt       3   5.335 ± 1.637   ms/op
ClientPb.getUser                          avgt       3   5.377 ± 2.684   ms/op
ClientPb.listUser                         avgt       3   6.203 ± 0.651   ms/op
ClientPb.createUser                     sample  175133   5.474 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.575           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.652           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.670           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.469           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.111           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.031           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  182711   5.251 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.126           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.666           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.603           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  174908   5.486 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.666           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.856           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.731           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.294           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.977           ms/op
ClientPb.listUser                       sample  151318   6.347 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.715           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.181           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.948           ms/op
