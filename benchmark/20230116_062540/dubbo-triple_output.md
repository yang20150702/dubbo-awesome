# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 5.651 ops/ms
# Warmup Iteration   3: 9.403 ops/ms
Iteration   1: 9.736 ops/ms
Iteration   2: 9.933 ops/ms
Iteration   3: 9.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.864 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (9.736, 9.864, 9.933), stdev = 0.112
  CI (99.9%): [7.829, 11.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ops/ms
# Warmup Iteration   2: 9.363 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.507 ±(99.9%) 4.763 ops/ms [Average]
  (min, avg, max) = (10.238, 10.507, 10.760), stdev = 0.261
  CI (99.9%): [5.744, 15.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ops/ms
# Warmup Iteration   2: 9.803 ops/ms
# Warmup Iteration   3: 9.753 ops/ms
Iteration   1: 10.050 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.209 ±(99.9%) 5.817 ops/ms [Average]
  (min, avg, max) = (10.002, 10.209, 10.576), stdev = 0.319
  CI (99.9%): [4.393, 16.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 7.923 ops/ms
# Warmup Iteration   3: 8.124 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.377 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.520 ±(99.9%) 2.302 ops/ms [Average]
  (min, avg, max) = (8.377, 8.520, 8.614), stdev = 0.126
  CI (99.9%): [6.218, 10.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.498 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.008 ms/op
Iteration   1: 3.225 ±(99.9%) 0.007 ms/op
Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
Iteration   3: 3.141 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.199 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.141, 3.199, 3.230), stdev = 0.050
  CI (99.9%): [2.280, 4.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.004 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.058 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.048, 3.058, 3.073), stdev = 0.013
  CI (99.9%): [2.817, 3.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.214 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.165 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.136, 3.165, 3.214), stdev = 0.042
  CI (99.9%): [2.397, 3.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.632 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.005 ms/op
Iteration   1: 3.716 ±(99.9%) 0.007 ms/op
Iteration   2: 3.727 ±(99.9%) 0.010 ms/op
Iteration   3: 3.742 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.728 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.716, 3.728, 3.742), stdev = 0.013
  CI (99.9%): [3.494, 3.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.011 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 23.135 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  18.056 ms/op
                 createUser·p0.9999: 22.712 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  11.110 ms/op
                 createUser·p0.9999: 19.199 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299812
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21201 
    [ 2.500,  5.000) = 273076 
    [ 5.000,  7.500) = 4647 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.082 ms/op
     p(99.9900) =     22.676 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.660 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.664 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.791 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 20.518 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  12.332 ms/op
                 existUser·p0.9999: 21.782 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.172 ms/op
                 existUser·p0.9999: 21.750 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303604
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19615 
    [ 2.500,  5.000) = 276786 
    [ 5.000,  7.500) = 6418 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.722 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.507 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.010 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  18.424 ms/op
                 getUser·p0.9999: 20.645 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.977 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 23.054 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  15.240 ms/op
                 getUser·p0.9999: 20.522 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296857
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14957 
    [ 2.500,  5.000) = 274149 
    [ 5.000,  7.500) = 6987 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     15.972 ms/op
     p(99.9900) =     22.096 ms/op
     p(99.9990) =     23.605 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.231 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.268 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 19.799 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.718 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 19.249 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257752
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 250872 
    [ 5.000,  7.500) = 4428 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.782 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.864 ± 2.036  ops/ms
ClientPb.existUser                       thrpt       3  10.507 ± 4.763  ops/ms
ClientPb.getUser                         thrpt       3  10.209 ± 5.817  ops/ms
ClientPb.listUser                        thrpt       3   8.520 ± 2.302  ops/ms
ClientPb.createUser                       avgt       3   3.199 ± 0.919   ms/op
ClientPb.existUser                        avgt       3   3.058 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   3.165 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   3.728 ± 0.235   ms/op
ClientPb.createUser                     sample  299812   3.200 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.752           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.676           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  303604   3.159 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.996           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.722           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  296857   3.232 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.096           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.019           ms/op
ClientPb.listUser                       sample  257752   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.592           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.300           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
