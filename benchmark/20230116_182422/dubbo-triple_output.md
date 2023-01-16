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
# Warmup Iteration   1: 2.109 ops/ms
# Warmup Iteration   2: 4.649 ops/ms
# Warmup Iteration   3: 8.695 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 9.143 ops/ms
Iteration   3: 9.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.199 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (9.139, 9.199, 9.314), stdev = 0.100
  CI (99.9%): [7.377, 11.020] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 8.710 ops/ms
# Warmup Iteration   3: 9.938 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.717 ops/ms
Iteration   3: 9.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 2.287 ops/ms [Average]
  (min, avg, max) = (9.549, 9.686, 9.794), stdev = 0.125
  CI (99.9%): [7.400, 11.973] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 8.268 ops/ms
# Warmup Iteration   3: 9.100 ops/ms
Iteration   1: 9.096 ops/ms
Iteration   2: 9.105 ops/ms
Iteration   3: 9.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.238 ±(99.9%) 4.339 ops/ms [Average]
  (min, avg, max) = (9.096, 9.238, 9.512), stdev = 0.238
  CI (99.9%): [4.899, 13.577] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.564 ops/ms
# Warmup Iteration   2: 6.838 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 7.779 ops/ms
Iteration   3: 7.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.800 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (7.756, 7.800, 7.866), stdev = 0.058
  CI (99.9%): [6.738, 8.863] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.263 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.005 ms/op
Iteration   1: 3.493 ±(99.9%) 0.009 ms/op
Iteration   2: 3.463 ±(99.9%) 0.012 ms/op
Iteration   3: 3.444 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.467 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.444, 3.467, 3.493), stdev = 0.025
  CI (99.9%): [3.012, 3.921] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.140 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.004 ms/op
Iteration   1: 3.316 ±(99.9%) 0.004 ms/op
Iteration   2: 3.391 ±(99.9%) 0.004 ms/op
Iteration   3: 3.313 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.340 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.313, 3.340, 3.391), stdev = 0.044
  CI (99.9%): [2.529, 4.151] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.132 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.005 ms/op
Iteration   1: 3.462 ±(99.9%) 0.007 ms/op
Iteration   2: 3.344 ±(99.9%) 0.006 ms/op
Iteration   3: 3.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.344, 3.419, 3.462), stdev = 0.066
  CI (99.9%): [2.223, 4.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.034 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.010 ms/op
Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
Iteration   2: 3.945 ±(99.9%) 0.013 ms/op
Iteration   3: 3.896 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.896, 3.956, 4.027), stdev = 0.067
  CI (99.9%): [2.741, 5.171] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.156 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.010 ms/op
Iteration   1: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  21.717 ms/op
                 createUser·p0.9999: 31.654 ms/op
                 createUser·p1.00:   32.866 ms/op

Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  23.378 ms/op
                 createUser·p0.9999: 29.933 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 3.530 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.520 ms/op
                 createUser·p0.999:  23.638 ms/op
                 createUser·p0.9999: 31.357 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275741
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1858 
    [ 2.500,  5.000) = 267900 
    [ 5.000,  7.500) = 4656 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     21.996 ms/op
     p(99.9900) =     31.054 ms/op
     p(99.9990) =     32.686 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.208 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.041 ms/op
                 existUser·p0.9999: 31.335 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   2: 3.354 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  20.998 ms/op
                 existUser·p0.9999: 54.032 ms/op
                 existUser·p1.00:   54.788 ms/op

Iteration   3: 3.420 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  23.728 ms/op
                 existUser·p0.9999: 28.279 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286116
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 279697 
    [ 5.000, 10.000) = 6002 
    [10.000, 15.000) = 162 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 8 
    [50.000, 55.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     45.241 ms/op
     p(99.9990) =     54.788 ms/op
     p(99.9999) =     54.788 ms/op
    p(100.0000) =     54.788 ms/op


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
# Warmup Iteration   1: 11.330 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.011 ms/op
Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  21.229 ms/op
                 getUser·p0.9999: 24.123 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.917 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  23.967 ms/op
                 getUser·p0.9999: 31.419 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   3: 3.632 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  22.181 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265029
  mean =      3.620 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6623 
    [ 2.500,  5.000) = 247662 
    [ 5.000,  7.500) = 9248 
    [ 7.500, 10.000) = 998 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     22.083 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     31.926 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 12.767 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.398 ms/op
                 listUser·p0.999:  20.166 ms/op
                 listUser·p0.9999: 26.969 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.067 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 18.046 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 4.113 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.175 ms/op
                 listUser·p0.9999: 16.487 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235994
  mean =      4.066 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 227124 
    [ 5.000,  7.500) = 6629 
    [ 7.500, 10.000) = 1435 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.390 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     24.884 ms/op
     p(99.9990) =     27.377 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.199 ± 1.822  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 2.287  ops/ms
ClientPb.getUser                         thrpt       3   9.238 ± 4.339  ops/ms
ClientPb.listUser                        thrpt       3   7.800 ± 1.063  ops/ms
ClientPb.createUser                       avgt       3   3.467 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   3.340 ± 0.811   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 1.196   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 1.215   ms/op
ClientPb.createUser                     sample  275741   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.982           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.996           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.054           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.866           ms/op
ClientPb.existUser                      sample  286116   3.356 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.001           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          45.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          54.788           ms/op
ClientPb.getUser                        sample  265029   3.620 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.032           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.083           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.507           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  235994   4.066 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.622           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.390           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.884           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
