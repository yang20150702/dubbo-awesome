# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.613 ops/ms
# Warmup Iteration   2: 6.298 ops/ms
# Warmup Iteration   3: 9.485 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.800 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.806 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (9.646, 9.806, 9.973), stdev = 0.164
  CI (99.9%): [6.820, 12.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.520 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (10.385, 10.520, 10.597), stdev = 0.117
  CI (99.9%): [8.383, 12.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.003 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.200 ±(99.9%) 3.199 ops/ms [Average]
  (min, avg, max) = (10.003, 10.200, 10.341), stdev = 0.175
  CI (99.9%): [7.001, 13.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 8.334 ops/ms
Iteration   1: 8.552 ops/ms
Iteration   2: 8.673 ops/ms
Iteration   3: 8.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.672 ±(99.9%) 2.192 ops/ms [Average]
  (min, avg, max) = (8.552, 8.672, 8.792), stdev = 0.120
  CI (99.9%): [6.480, 10.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.389 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.005 ms/op
Iteration   1: 3.240 ±(99.9%) 0.007 ms/op
Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.167 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (3.116, 3.167, 3.240), stdev = 0.065
  CI (99.9%): [1.978, 4.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.937 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.004 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
Iteration   3: 3.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.085 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.057, 3.085, 3.113), stdev = 0.028
  CI (99.9%): [2.574, 3.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.005 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.163 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.133 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.084, 3.133, 3.163), stdev = 0.042
  CI (99.9%): [2.358, 3.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.383 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.006 ms/op
Iteration   1: 3.719 ±(99.9%) 0.006 ms/op
Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
Iteration   3: 3.860 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (3.691, 3.757, 3.860), stdev = 0.090
  CI (99.9%): [2.109, 5.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.495 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.010 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  12.333 ms/op
                 createUser·p0.9999: 21.989 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  17.427 ms/op
                 createUser·p0.9999: 21.268 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.139 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  16.802 ms/op
                 createUser·p0.9999: 31.812 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300886
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14205 
    [ 2.500,  5.000) = 282098 
    [ 5.000,  7.500) = 3711 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.763 ms/op
     p(99.9900) =     29.849 ms/op
     p(99.9990) =     32.209 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.398 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.255 ms/op
                 existUser·p0.9999: 19.915 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 3.035 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  10.497 ms/op
                 existUser·p0.9999: 21.788 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315339
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20493 
    [ 2.500,  5.000) = 290079 
    [ 5.000,  7.500) = 4053 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     10.250 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.305 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.957 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  16.774 ms/op
                 getUser·p0.9999: 29.721 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.269 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.942 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.924 ms/op
                 getUser·p0.999:  11.913 ms/op
                 getUser·p0.9999: 18.421 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300377
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14984 
    [ 2.500,  5.000) = 276893 
    [ 5.000,  7.500) = 7579 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     29.102 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.252 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.012 ms/op
Iteration   1: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.907 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.648 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.067 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 15.696 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   3: 3.585 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.039 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  11.572 ms/op
                 listUser·p0.9999: 14.091 ms/op
                 listUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262134
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 53 
    [ 2.500,  3.750) = 212796 
    [ 3.750,  5.000) = 41037 
    [ 5.000,  6.250) = 4831 
    [ 6.250,  7.500) = 1919 
    [ 7.500,  8.750) = 653 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 168 
    [13.750, 15.000) = 108 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     17.779 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.806 ± 2.986  ops/ms
ClientPb.existUser                       thrpt       3  10.520 ± 2.137  ops/ms
ClientPb.getUser                         thrpt       3  10.200 ± 3.199  ops/ms
ClientPb.listUser                        thrpt       3   8.672 ± 2.192  ops/ms
ClientPb.createUser                       avgt       3   3.167 ± 1.189   ms/op
ClientPb.existUser                        avgt       3   3.085 ± 0.511   ms/op
ClientPb.getUser                          avgt       3   3.133 ± 0.775   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 1.648   ms/op
ClientPb.createUser                     sample  300886   3.187 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.763           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.849           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  315339   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.250           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.741           ms/op
ClientPb.getUser                        sample  300377   3.196 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.269           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.762           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.102           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  262134   3.661 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.537           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.779           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.923           ms/op
