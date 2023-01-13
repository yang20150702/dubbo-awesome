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
# Warmup Iteration   1: 2.480 ops/ms
# Warmup Iteration   2: 6.536 ops/ms
# Warmup Iteration   3: 9.407 ops/ms
Iteration   1: 9.783 ops/ms
Iteration   2: 10.095 ops/ms
Iteration   3: 9.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.912 ±(99.9%) 2.971 ops/ms [Average]
  (min, avg, max) = (9.783, 9.912, 10.095), stdev = 0.163
  CI (99.9%): [6.941, 12.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 9.957 ops/ms
Iteration   1: 10.012 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.332 ±(99.9%) 7.127 ops/ms [Average]
  (min, avg, max) = (10.012, 10.332, 10.767), stdev = 0.391
  CI (99.9%): [3.204, 17.459] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.183 ops/ms
# Warmup Iteration   2: 9.315 ops/ms
# Warmup Iteration   3: 9.693 ops/ms
Iteration   1: 10.004 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.934 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (9.852, 9.934, 10.004), stdev = 0.077
  CI (99.9%): [8.532, 11.337] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.280 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.339 ops/ms
Iteration   2: 8.611 ops/ms
Iteration   3: 8.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.569 ±(99.9%) 3.877 ops/ms [Average]
  (min, avg, max) = (8.339, 8.569, 8.757), stdev = 0.213
  CI (99.9%): [4.692, 12.446] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.006 ms/op
Iteration   1: 3.235 ±(99.9%) 0.005 ms/op
Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
Iteration   3: 3.359 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.253 ±(99.9%) 1.783 ms/op [Average]
  (min, avg, max) = (3.166, 3.253, 3.359), stdev = 0.098
  CI (99.9%): [1.470, 5.036] (assumes normal distribution)


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
# Warmup Iteration   1: 7.725 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.003 ms/op
Iteration   1: 3.131 ±(99.9%) 0.005 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 2.955 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.062 ±(99.9%) 1.704 ms/op [Average]
  (min, avg, max) = (2.955, 3.062, 3.131), stdev = 0.093
  CI (99.9%): [1.357, 4.766] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.588 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.005 ms/op
Iteration   2: 3.177 ±(99.9%) 0.004 ms/op
Iteration   3: 3.138 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.139 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.103, 3.139, 3.177), stdev = 0.037
  CI (99.9%): [2.457, 3.822] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.973 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.003 ms/op
Iteration   1: 3.700 ±(99.9%) 0.007 ms/op
Iteration   2: 3.794 ±(99.9%) 0.006 ms/op
Iteration   3: 3.707 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.734 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.700, 3.734, 3.794), stdev = 0.052
  CI (99.9%): [2.784, 4.683] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 22.298 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  10.646 ms/op
                 createUser·p0.9999: 24.989 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  15.581 ms/op
                 createUser·p0.9999: 29.005 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296934
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18292 
    [ 2.500,  5.000) = 271657 
    [ 5.000,  7.500) = 5993 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     16.075 ms/op
     p(99.9900) =     27.422 ms/op
     p(99.9990) =     29.722 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 6.706 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  8.467 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.297 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  13.988 ms/op
                 existUser·p0.9999: 22.866 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.137 ms/op
                 existUser·p0.9999: 22.069 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316205
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25910 
    [ 2.500,  5.000) = 285846 
    [ 5.000,  7.500) = 3887 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.199 ms/op
     p(95.0000) =      3.412 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     13.726 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.637 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 8.552 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  13.631 ms/op
                 getUser·p0.9999: 20.324 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  9.667 ms/op
                 getUser·p0.9999: 23.552 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 22.214 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301027
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19844 
    [ 2.500,  5.000) = 273058 
    [ 5.000,  7.500) = 7127 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     13.204 ms/op
     p(99.9900) =     22.312 ms/op
     p(99.9990) =     24.837 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 8.145 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.016 ms/op
Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.094 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.260 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.276 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256081
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 247412 
    [ 5.000,  7.500) = 6827 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     22.721 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.912 ± 2.971  ops/ms
ClientPb.existUser                       thrpt       3  10.332 ± 7.127  ops/ms
ClientPb.getUser                         thrpt       3   9.934 ± 1.403  ops/ms
ClientPb.listUser                        thrpt       3   8.569 ± 3.877  ops/ms
ClientPb.createUser                       avgt       3   3.253 ± 1.783   ms/op
ClientPb.existUser                        avgt       3   3.062 ± 1.704   ms/op
ClientPb.getUser                          avgt       3   3.139 ± 0.683   ms/op
ClientPb.listUser                         avgt       3   3.734 ± 0.950   ms/op
ClientPb.createUser                     sample  296934   3.233 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.075           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.422           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  316205   3.034 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.725           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  301027   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.204           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.312           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.428           ms/op
ClientPb.listUser                       sample  256081   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.174           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.721           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
