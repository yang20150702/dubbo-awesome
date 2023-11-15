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
# Warmup Iteration   1: 5.087 ops/ms
# Warmup Iteration   2: 12.371 ops/ms
# Warmup Iteration   3: 12.272 ops/ms
Iteration   1: 12.581 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.671 ±(99.9%) 1.424 ops/ms [Average]
  (min, avg, max) = (12.581, 12.671, 12.725), stdev = 0.078
  CI (99.9%): [11.246, 14.095] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.939 ops/ms
# Warmup Iteration   2: 12.996 ops/ms
# Warmup Iteration   3: 13.079 ops/ms
Iteration   1: 13.075 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.958 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (12.884, 12.958, 13.075), stdev = 0.102
  CI (99.9%): [11.097, 14.820] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.297 ops/ms
# Warmup Iteration   3: 12.529 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.689 ops/ms
Iteration   3: 12.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.679 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (12.624, 12.679, 12.724), stdev = 0.051
  CI (99.9%): [11.752, 13.605] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.862 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.517 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.628 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (10.517, 10.628, 10.716), stdev = 0.101
  CI (99.9%): [8.783, 12.473] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (2.492, 2.537, 2.592), stdev = 0.051
  CI (99.9%): [1.616, 3.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.003 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.450, 2.454, 2.463), stdev = 0.007
  CI (99.9%): [2.324, 2.585] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.931 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.003 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.438, 2.447, 2.457), stdev = 0.010
  CI (99.9%): [2.273, 2.622] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.955, 2.969, 2.988), stdev = 0.017
  CI (99.9%): [2.659, 3.279] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.362 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 13.358 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.747 ms/op
                 createUser·p0.999:  10.153 ms/op
                 createUser·p0.9999: 12.853 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  8.318 ms/op
                 createUser·p0.9999: 10.697 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376586
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 181938 
    [ 2.500,  3.750) = 190778 
    [ 3.750,  5.000) = 2944 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.211 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  7.972 ms/op
                 existUser·p0.9999: 12.292 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  6.683 ms/op
                 existUser·p0.9999: 10.781 ms/op
                 existUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390346
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 193116 
    [ 2.500,  3.750) = 193321 
    [ 3.750,  5.000) = 2891 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.190 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.342 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  11.592 ms/op
                 getUser·p0.9999: 13.749 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  9.245 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  6.841 ms/op
                 getUser·p0.9999: 12.225 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385290
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 190901 
    [ 2.500,  3.750) = 189851 
    [ 3.750,  5.000) = 3514 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 140 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.426 ms/op
     p(99.9900) =     13.705 ms/op
     p(99.9990) =     14.437 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.008 ms/op
Iteration   1: 2.934 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.752 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.970 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 18.358 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.648 ms/op
                 listUser·p0.9999: 12.032 ms/op
                 listUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324567
  mean =      2.955 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 102862 
    [ 2.500,  3.750) = 186262 
    [ 3.750,  5.000) = 29004 
    [ 5.000,  6.250) = 5173 
    [ 6.250,  7.500) = 488 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 270 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     15.261 ms/op
     p(99.9990) =     18.687 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.671 ± 1.424  ops/ms
ClientPb.existUser                       thrpt       3  12.958 ± 1.861  ops/ms
ClientPb.getUser                         thrpt       3  12.679 ± 0.927  ops/ms
ClientPb.listUser                        thrpt       3  10.628 ± 1.845  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.921   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.310   ms/op
ClientPb.createUser                     sample  376586   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.211           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.992           ms/op
ClientPb.existUser                      sample  390346   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.866           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.500           ms/op
ClientPb.getUser                        sample  385290   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.719           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.426           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.705           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  324567   2.955 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.261           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.809           ms/op
